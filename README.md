# GitHub Setup & Configuration

## Current GitHub Settings

### Account Information
- **GitHub Username:** ByteStackr
- **Repository URL:** https://github.com/ByteStackr/demo

### Git Configuration (Local)
```bash
git config --global user.name "ByteStackr"
git config --global user.email "229177070+ByteStackr@users.noreply.github.com"
```

### GitHub CLI Authentication
- **Status:** ✅ Authenticated as ByteStackr
- **Installation:** GitHub CLI v2.78.0 installed via `winget install GitHub.cli`

## Quick Setup Commands for New Device

### 1. Install GitHub CLI
```bash
winget install GitHub.cli
```

### 2. Authenticate with GitHub
```bash
gh auth login
```
Follow the device code authentication process.

### 3. Configure Git Identity
```bash
git config --global user.name "ByteStackr"
git config --global user.email "229177070+ByteStackr@users.noreply.github.com"
```

### 4. Verify Configuration
```bash
git config --global user.name
git config --global user.email
gh auth status
```

## Email Privacy Settings
- **Primary Email:** vkhcgf@gmail.com (private)
- **No-Reply Email:** 229177070+ByteStackr@users.noreply.github.com
- **Setting:** Email privacy enabled (recommended)

## Common Git Operations
```bash
# Clone repository
gh repo clone ByteStackr/demo

# Create new repository
gh repo create repo-name --public

# Check status
git status
gh auth status

# Push changes
git add .
git commit -m "Your commit message"
git push
```

## Environment Details
- **Platform:** Windows + XAMPP
- **Working Directory:** C:\xampp\htdocs\apps\bbrefactored\
- **Git Version:** 2.51.0.windows.1
- **GitHub CLI Path:** C:\Program Files\GitHub CLI\gh.exe

## Troubleshooting

### Email Privacy Issues
If you get "GH007: Your push would publish a private email address":
1. Ensure you're using the no-reply email: `229177070+ByteStackr@users.noreply.github.com`
2. Check GitHub settings at: https://github.com/settings/emails

### GitHub CLI Not Found
After installation, restart your terminal or use full path:
```bash
"C:\Program Files\GitHub CLI\gh.exe" auth login
```

---
*Last updated: 2025-09-05*
*Created for consistent GitHub setup across devices*