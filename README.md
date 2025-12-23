# Sofarak Snacks Landing Page

A mobile-first WhatsApp ordering landing page for **Sofarak**, a warm local snack brand selling plantain chips, potato chips and chin chin.

## Tech stack

- Pure static site (no build step needed)
- `index.html` + `styles.css` + images in `assets/`
- WhatsApp CTAs with prefilled messages

## Running locally

Open `index.html` directly in your browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploying to Vercel

This is a static project, so no framework or build command is required.

1. Push this folder to GitHub (see commands below).
2. In Vercel, click **New Project** and import the `sofarak` repository.
3. Framework preset: **Other**.
4. Build command: **None**.
5. Output directory: `.` (project root).

Vercel will serve `index.html` from the root along with the `assets` folder.

## Pushing to GitHub

From the project directory:

```bash
cd /Users/user/Desktop/sofarakchips

git init
git add .
git commit -m "Initial Sofarak landing page"
git branch -M main
git remote add origin https://github.com/jungle0011/sofarak.git
git push -u origin main
```

After this, you can import the `jungle0011/sofarak` repo into Vercel.
