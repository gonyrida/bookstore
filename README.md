# Book Store Website

A static website for a book store, featuring sections for featured books, new arrivals, reviews, and a blog.

## Deployment Instructions

### Option 1: GitHub Pages

1. Create a new repository on GitHub.
2. Upload all files (`book.html`, `style.css`, and the `image/` folder) to the repository.
3. Go to Settings > Pages.
4. Under Source, select "Deploy from a branch".
5. Select the main branch and click Save.
6. Your site will be live at `https://<username>.github.io/<repository-name>/`.

### Option 2: Netlify

1. Sign up for a free account at [Netlify](https://netlify.com).
2. Drag and drop the project folder (containing `book.html`, `style.css`, and `image/`) onto the Netlify dashboard.
3. Netlify will automatically deploy the site and provide a live URL.

### Option 3: Other Static Hosting

- Upload the files to any static hosting service like Vercel, Surge, or Firebase Hosting.
- Ensure the `image/` folder is included for images to load properly.

## File Structure

- `book.html`: Main HTML file
- `style.css`: Stylesheet
- `image/`: Folder containing all images
- `README.md`: This file

## Notes

- All image paths are relative, so the site works without a server.
- Open `book.html` in a browser to view locally.
