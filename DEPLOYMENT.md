# Deploying Your Blog to GitHub Pages

Follow these simple steps to get your blog live on the internet for free!

## Step 1: Create a GitHub Repository

1. Go to [GitHub.com](https://github.com) and sign in
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Name your repository (e.g., `my-blog` or `och-inget-mer-hande`)
5. Make it **Public** (required for free GitHub Pages)
6. Don't initialize with README (since you already have files)
7. Click "Create repository"

## Step 2: Upload Your Files

### Option A: Using GitHub Web Interface (Easiest)

1. In your new repository, click "uploading an existing file"
2. Drag and drop all your blog files:
   - `index.html`
   - `styles.css`
   - `README.md`
   - `post-template.html`
   - `DEPLOYMENT.md`
   - The entire `images/` folder
3. Add a commit message like "Initial blog setup"
4. Click "Commit changes"

### Option B: Using Git (If you have Git installed)

```bash
# Clone the repository
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name

# Copy your blog files into this folder
# Then add and commit them
git add .
git commit -m "Initial blog setup"
git push origin main
```

## Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings" tab
3. Scroll down to "Pages" section (in the left sidebar)
4. Under "Source", select "Deploy from a branch"
5. Choose "main" branch
6. Select "/ (root)" folder
7. Click "Save"

## Step 4: Wait and Access Your Blog

1. GitHub will show a message that your site is being built
2. Wait a few minutes (usually 2-5 minutes)
3. Your blog will be available at: `https://yourusername.github.io/your-repo-name`

## Step 5: Custom Domain (Optional)

If you want to use a custom domain:

1. Buy a domain (from Namecheap, GoDaddy, etc.)
2. In GitHub Pages settings, enter your domain in the "Custom domain" field
3. Add a file called `CNAME` to your repository with just your domain name
4. Configure your domain's DNS settings to point to GitHub Pages

## Updating Your Blog

To add new posts or make changes:

1. Edit the files locally
2. Upload the updated files to GitHub (same as Step 2)
3. Your changes will automatically appear on your live site within a few minutes

## Troubleshooting

- **Site not showing up**: Check that your repository is public
- **Images not loading**: Make sure image paths are correct and images are in the `images/` folder
- **Styling issues**: Clear your browser cache or try incognito mode
- **404 errors**: Make sure your main file is named `index.html`

## Alternative Free Hosting

If GitHub Pages doesn't work for you:

### Netlify
1. Go to [netlify.com](https://netlify.com)
2. Drag and drop your blog folder
3. Get a free URL instantly

### Vercel
1. Go to [vercel.com](https://vercel.com)
2. Connect your GitHub repository
3. Automatic deployments on every update

---

Your blog is now live! Share your URL with friends and start posting regularly. Remember, consistency is key - even if it's just a simple observation about your day.
