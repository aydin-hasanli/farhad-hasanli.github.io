# Farhad Hasanli — Research Website

A simple static research portfolio designed for GitHub Pages.

## Files

- `index.html` — main website content
- `styles.css` — layout and visual styling
- `script.js` — mobile navigation and footer year
- `.gitignore` — common ignored files

## Before publishing

Search `index.html` for the word `Replace` or `placeholder` and update:

1. LinkedIn URL
2. Email address
3. CV link
4. Exact master's thesis title
5. Any project descriptions you want to refine

The GitHub link is currently set to:

`https://github.com/aydin-hasanli`

Change it if needed.

## Repository

This site is intended for:

```text
https://github.com/aydin-hasanli/farhad-hasanli.github.io
```

## Publish with GitHub Pages

After creating the repository:

```bash
git init
git add .
git commit -m "Initial research website"
git branch -M main
git remote add origin https://github.com/aydin-hasanli/farhad-hasanli.github.io.git
git push -u origin main
```

If you already cloned the repository, you do **not** need to run `git init` or add the remote again.

Then in GitHub:

1. Open the repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select `main` and `/ (root)`.
5. Save.

Because the GitHub account username is `aydin-hasanli` while this repository is
`farhad-hasanli.github.io`, GitHub treats it as a project Pages site.

The default Pages URL will normally be:

`https://aydin-hasanli.github.io/farhad-hasanli.github.io/`

If you later connect a custom domain, that domain can become the public website address.

## Adding a CV

Create an `assets` folder and put your CV inside:

```text
assets/Farhad_Hasanli_CV.pdf
```

Then replace the placeholder CV link in `index.html` with:

```html
<a href="assets/Farhad_Hasanli_CV.pdf" target="_blank">
  CV
  <span aria-hidden="true">↗</span>
</a>
```

## Adding research images later

A useful structure is:

```text
assets/
├── Farhad_Hasanli_CV.pdf
├── dgsem/
│   ├── double-mach-reflection.png
│   ├── kelvin-helmholtz.png
│   └── cavity.png
└── profile/
    └── farhad.jpg
```

You can then add figures to the Research Work section without changing the overall site structure.
