# Academic Personal Website

A simple, traditional academic homepage prepared for GitHub Pages.

## Edit your information

Open `index.html` in a text editor and replace the placeholder content:

- `Your Name`
- position, department, institution, and biography
- contact details
- teaching entries
- publications and thesis entries
- every `href="#"` placeholder

### Add your photograph

The page currently contains an embedded placeholder portrait, so it works as a single file.

To use your own image:

1. Put the image in this repository, for example as `profile.jpg`.
2. Find the `<img class="profile-photo" ...>` element in `index.html`.
3. Replace its long `src="data:image..."` value with:

```html
src="profile.jpg"
```

## Publish with GitHub Pages

### Option A: Personal homepage

1. Create a public GitHub repository named exactly `YOUR-USERNAME.github.io`.
2. Upload all files from this folder to the repository root.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`, then save.
6. Your site will be available at `https://YOUR-USERNAME.github.io/`.

### Option B: Project homepage

1. Create a public repository with any name, such as `my-website`.
2. Upload all files from this folder.
3. Enable Pages from the `main` branch and `/ (root)`.
4. Your site will be available at `https://YOUR-USERNAME.github.io/my-website/`.

## Important

Keep `index.html` in the repository root. Do not upload the containing folder as an extra nested folder.
