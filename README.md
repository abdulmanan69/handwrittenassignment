# Text to Handwritten Assignment

A static, client‑side web app that turns typed content into a handwritten‑style assignment. No backend or Flask required—just open index.html.

## Features
- Rich text editing with Quill (bold, lists, alignment, etc.)
- LaTeX math rendering via KaTeX ($...$)
- Drawing canvas (pen/eraser/shapes) with undo/redo and insert into page
- Page setup: size, orientation, margins, line spacing, custom background
- Custom fonts (upload .ttf) and preset handwriting fonts
- Multi‑page navigation and export (current page as image, all pages to PDF)

## Run locally
- Double‑click index.html (or open in your browser). That’s it.

## Deploy to GitHub Pages
1. Create a repo on GitHub and copy its URL.
2. Initialize and push this folder (already initialized here). If needed:
   - git remote add origin <your_repo_url>
   - git push -u origin main
3. On GitHub: Settings → Pages → Source: “Deploy from a branch” → Branch: main → Folder: /(root).
4. Wait for the green Pages badge; your site will be live at https://<user>.github.io/<repo>/

## Structure
- index.html — main app
- static/final.css — styles
- static/final.js — app logic
- static/icons, static/fonts — assets

## Credits
- Created with ❤ — dedicated to Werda
- Built by [Abdul Manan](https://github.com/abdulmanan69)
