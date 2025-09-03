# Deployment Guide

## GitHub Pages Setup

### Step 1: Create GitHub Repository
1. Go to [GitHub](https://github.com) and create a new repository
2. Name it `your-username.github.io` (replace with your actual username) for a personal site
3. Or use any repository name for a project site

### Step 2: Upload Files
1. Clone your repository locally
2. Copy all files from this template to your repository
3. Commit and push your changes

### Step 3: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click on "Settings" tab
3. Scroll down to "Pages" section
4. Under "Source", select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Click "Save"

### Step 4: Access Your Site
- Your site will be available at:
  - `https://your-username.github.io` (for personal sites)
  - `https://your-username.github.io/repository-name` (for project sites)

## Custom Domain (Optional)

### Step 1: Add Custom Domain
1. In your repository Settings → Pages
2. Add your custom domain in the "Custom domain" field
3. Click "Save"

### Step 2: Configure DNS
1. Add a CNAME record pointing to `your-username.github.io`
2. Wait for DNS propagation (can take up to 24 hours)

## File Structure for GitHub Pages

```
your-repository/
├── index.html          # Main page (will be served as homepage)
├── aleksandra.html     # Example page
├── styles.css          # Styles
├── script.js           # JavaScript
├── README.md           # Documentation
└── .gitignore          # Git ignore file
```

## Tips

1. **Use index.html as your main page** - GitHub Pages serves this as the homepage
2. **Keep file names lowercase** - Some servers are case-sensitive
3. **Test locally** - Open index.html in your browser to preview changes
4. **Commit frequently** - Each commit triggers a new deployment

## Troubleshooting

### Site Not Loading
- Check if GitHub Pages is enabled in repository settings
- Verify the branch and folder are correctly selected
- Wait a few minutes for deployment to complete

### Changes Not Appearing
- Clear your browser cache
- Check if the commit was pushed successfully
- GitHub Pages can take a few minutes to update

### Custom Domain Issues
- Verify DNS settings are correct
- Check if the domain is properly configured in repository settings
- Wait for DNS propagation

## Performance Tips

1. **Optimize images** - Compress images before uploading
2. **Minimize CSS/JS** - Remove unused code
3. **Use CDN** - Consider using a CDN for faster loading
4. **Enable compression** - GitHub Pages automatically compresses files

## Security

- Never commit sensitive information (passwords, API keys)
- Use environment variables for sensitive data
- Regularly update dependencies if using any
