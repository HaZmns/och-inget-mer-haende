# och inget mer hände

A minimalistic personal blog with clean design and artsy typography.

## Features

- ✨ Clean, minimalistic design with white background
- 🎨 Artsy typography using Playfair Display and Source Sans Pro fonts
- 📱 Fully responsive design for mobile and desktop
- 🖼️ Easy image upload and display
- 🚀 Ready for GitHub Pages deployment
- 📝 Individual post files for easy management
- 🔗 Post previews with links to full articles

## Getting Started

### Local Development

1. Clone or download this repository
2. Open `index.html` in your web browser
3. Start customizing the content!

### Adding New Blog Posts

Each blog post is now in its own file for easier management. To add a new post:

1. **Create the post file:**
   - Copy the template from `post-template.html`
   - Create a new file in the `posts/` folder with a descriptive name (e.g., `my-new-post.html`)
   - Update the title, date, content, and image

2. **Add a preview to the homepage:**
   - Edit `index.html`
   - Add a new `<article class="post-preview">` section
   - Include a link to your new post file
   - Add an excerpt and image preview

### File Structure

```
blog/
├── index.html                    # Main blog page with post previews
├── styles.css                    # CSS styles
├── post-template.html            # Template for new posts
├── posts/                        # Individual post files
│   ├── första-veckan.html
├── images/                       # Image folder
└── README.md                     # This file
```

### Example: Adding a New Post

1. **Create the post file** (`posts/my-weekend-walk.html`):
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>My Weekend Walk - och inget mer hände</title>
    <link rel="stylesheet" href="../styles.css">
    <!-- ... other head elements ... -->
</head>
<body>
    <header>
        <div class="container">
            <h1 class="blog-title"><a href="../index.html">och inget mer hände</a></h1>
        </div>
    </header>
    <main class="container">
        <article class="post">
            <div class="post-meta">
                <time datetime="2024-01-22">January 22, 2024</time>
            </div>
            <h2 class="post-title">My Weekend Walk</h2>
            <div class="post-content">
                <p>Your blog post content here...</p>
            </div>
        </article>
    </main>
</body>
</html>
```

2. **Add preview to homepage** (in `index.html`):
```html
<article class="post-preview">
    <div class="post-meta">
        <time datetime="2024-01-22">January 22, 2024</time>
    </div>
    <h2 class="post-title">
        <a href="posts/my-weekend-walk.html">My Weekend Walk</a>
    </h2>
    <div class="post-excerpt">
        <p>Brief excerpt of your post...</p>
    </div>
    <div class="read-more">
        <a href="posts/my-weekend-walk.html">Read full post →</a>
    </div>
</article>
```

### Adding Images

1. Place your images in the `images/` folder
2. Reference them in your HTML using the path `../images/filename.jpg` (for post files)
3. Use descriptive alt text for accessibility
4. The `loading="lazy"` attribute helps with page performance

## Deployment

### GitHub Pages (Recommended)

1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to Settings → Pages
4. Select "Deploy from a branch"
5. Choose the `main` branch and `/ (root)` folder
6. Click "Save"
7. Your blog will be available at `https://yourusername.github.io/repository-name`

### Alternative Free Hosting Options

- **Netlify**: Drag and drop your folder to deploy
- **Vercel**: Connect your GitHub repository for automatic deployments
- **Firebase Hosting**: Free hosting with Google's platform

## Customization

### Colors and Typography

Edit `styles.css` to customize:
- Fonts (currently using Playfair Display and Source Sans Pro)
- Colors (currently using various shades of gray)
- Spacing and layout
- Responsive breakpoints

### Blog Title and Subtitle

Update the header section in `index.html` and all post files:
```html
<h1 class="blog-title"><a href="../index.html">och inget mer hände</a></h1>
<p class="blog-subtitle">...or updates on what I remember from last week in Stockholm</p>
```

## Tips for Weekly Blog Posts

1. **Keep it simple**: Focus on one idea or moment per post
2. **Use images**: Add relevant photos to make posts more engaging
3. **Be consistent**: Try to post on the same day each week
4. **Write naturally**: The blog name "och inget mer hände" (and nothing more happened) suggests embracing simple moments
5. **Optimize images**: Compress photos before uploading for faster loading
6. **Use descriptive filenames**: Make your post filenames clear and memorable

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## License

This project is open source and available under the [MIT License](LICENSE).

---

*"och inget mer hände" - and nothing more happened*
