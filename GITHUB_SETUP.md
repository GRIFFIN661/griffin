# GitHub Setup Instructions

## Step 1: Create GitHub Repository
1. Go to [GitHub.com](https://github.com)
2. Click "New repository" or go to https://github.com/new
3. Repository name: `blogging-platform` (or your preferred name)
4. Description: `Full-stack blogging platform with Spring Boot backend and React frontend`
5. Make it **Public** or **Private** (your choice)
6. **DO NOT** initialize with README, .gitignore, or license (we already have these)
7. Click "Create repository"

## Step 2: Connect Local Repository to GitHub
After creating the repository, run these commands in your project directory:

```bash
# Add GitHub repository as remote origin (replace YOUR_USERNAME and REPO_NAME)
git remote add origin https://github.com/YOUR_USERNAME/REPO_NAME.git

# Push to GitHub
git branch -M main
git push -u origin main
```

## Example Commands
If your GitHub username is `john` and repository name is `blogging-platform`:

```bash
git remote add origin https://github.com/john/blogging-platform.git
git branch -M main
git push -u origin main
```

## Step 3: Verify Upload
1. Refresh your GitHub repository page
2. You should see all your project files
3. The repository should show 115+ files

## Project Structure on GitHub
```
blogging-platform/
├── springapp/          # Spring Boot backend
├── reactapp/           # React frontend  
├── .github/workflows/  # CI/CD workflows
├── README.md          # Project documentation
├── SETUP.md           # Setup instructions
└── .gitignore         # Git ignore rules
```

## Next Steps After Upload
1. Update README.md with your specific setup instructions
2. Add repository URL to your project documentation
3. Consider setting up GitHub Actions for CI/CD
4. Add collaborators if working in a team

## Troubleshooting
- If you get authentication errors, make sure you're logged into GitHub
- Use personal access token instead of password for HTTPS
- Or set up SSH keys for easier authentication