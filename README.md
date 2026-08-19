# Huihui Qi — GitHub Pages academic website

This folder contains a simple academic website inspired by the two-column layout in the reference screenshot.

## Files

- `index.html` — homepage
- `publications.html` — publications
- `presentations.html` — conference presentations
- `style.css` — all styling
- `assets/profile-placeholder.svg` — replace with your own photo if desired

## How to use on GitHub Pages

1. Create a repository named `YOUR_GITHUB_USERNAME.github.io`.
2. Upload all files in this folder to the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`.
6. Save.

Your site will then be available at:

`https://YOUR_GITHUB_USERNAME.github.io/`

## Replace the profile photo

Put your portrait in `assets/`, for example:

`assets/profile.jpg`

Then change this line in all three HTML files:

```html
<img class="profile-photo" src="assets/profile-placeholder.svg" alt="Huihui Qi">
```

to:

```html
<img class="profile-photo" src="assets/profile.jpg" alt="Huihui Qi">
```

## Things you should edit

Search for and replace:

- `your-email@university.edu`
- affiliation / department
- Google Scholar URL
- CV URL
- GitHub URL
- LinkedIn URL
- publication titles / authors / journal names
- presentation titles / conference names

The Research section is intentionally written as a general paragraph and does **not** list Viral tools, MAPseq, Vocal learning, or Spatial transcriptomics.
