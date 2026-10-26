# ADVANCE PRECISION ENGINEERING — Personal Photo Portfolio

A simple, responsive static website made with HTML and CSS. No backend, database, login, or JavaScript features are required.

## Preview locally
1. Extract this folder.
2. Open `index.html` in a browser.
3. Internet access is needed for the sample Unsplash photos and Google Fonts.

## Replace the sample photos
The gallery currently uses sample photo URLs from Unsplash. To use your own:
1. Put your images in the `images` folder (for example `photo-01.jpg`).
2. In `index.html`, replace each `<img src="https://images.unsplash.com/...">` with `src="images/photo-01.jpg"`.
3. Update the `alt` text to describe your photo.
4. Keep image filenames simple: lowercase letters, numbers, and hyphens.

You can duplicate or remove a `<figure class="photo">...</figure>` block to add/remove gallery items.

## Publish with GitHub Pages
1. Sign in or create an account at https://github.com/
2. Create a new **public** repository. For the easiest URL, name it exactly:
   `YOUR-USERNAME.github.io`
3. Upload `index.html`, `style.css`, and the `images` folder (if you added local photos) to the repository root.
4. Open repository **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch `main` and folder `/ (root)`, then click **Save**.
7. Wait for GitHub Pages to publish. Your website URL will be:
   `https://YOUR-USERNAME.github.io/`
   Replace `YOUR-USERNAME` with your GitHub username.

If you use a repository with a different name, the URL will usually be:
`https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`

## Help Google discover the website
1. Open Google Search Console: https://search.google.com/search-console/
2. Add your published website as a **URL prefix** property.
3. Verify ownership using one of the methods Google offers (HTML file or meta tag are common for a static site).
4. Submit the URL: `https://YOUR-USERNAME.github.io/`
5. Google may take time to crawl and index it. Being indexed or ranking for a particular search is not guaranteed.
6. Use your real name / organization name consistently in the page title, heading, and description. Avoid publishing private contact details.

## Customize the site
- Site title and SEO description: top of `index.html` in `<title>` and `<meta name="description">`.
- Main heading: the `<h1>` in the hero section.
- About section: edit the paragraphs under `id="about"`.
- Gallery: edit the photo `<figure>` blocks under `id="gallery"`.
- Colors and fonts: edit variables near the top of `style.css`.

## Important
The displayed name **ADVANCE PRECISION ENGINEERING** is used as requested. If this is a company website rather than a personal portfolio, add accurate company details and use only photos/logos you have permission to publish.
