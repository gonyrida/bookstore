# Book Store Website

A static website for a book store, featuring sections for featured books, new arrivals, reviews, and a blog.

## Deployment Instructions

### Option 1: GitHub Pages

1. Create a new repository on GitHub (e.g., named "book-store" without spaces).
2. Upload all files (`index.html`, `style.css`, and the `image/` folder) to the repository root.
3. Go to Settings > Pages.
4. Under Source, select "Deploy from a branch".
5. Select the main branch and the root folder, then click Save.
6. Your site will be live at `https://<username>.github.io/<repository-name>/` (e.g., `https://username.github.io/book-store/`).

### Option 2: Netlify

1. Sign up for a free account at [Netlify](https://netlify.com).
2. Drag and drop the project folder (containing `index.html`, `style.css`, and `image/`) onto the Netlify dashboard.
3. Netlify will automatically deploy the site and provide a live URL.

### Option 3: Other Static Hosting

- Upload the files to any static hosting service like Vercel, Surge, or Firebase Hosting.
- Ensure the `image/` folder is included for images to load properly.
- For subdirectory deployments (e.g., if hosting under a path like `https://example.com/bookstore/`), update image paths in `index.html` from relative (e.g., "image/logo.jpg") to absolute or prefixed (e.g., "/bookstore/image/logo.jpg").

## File Structure

- `index.html`: Main HTML file
- `style.css`: Stylesheet
- `image/`: Folder containing all images
- `README.md`: This file

## Notes

- All image paths are relative, so the site works without a server when deployed from the root.
- Open `index.html` in a browser to view locally.
- If deploying to a subdirectory, adjust paths accordingly to avoid 404 errors on images.
