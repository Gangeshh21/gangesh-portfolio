# Gangesh Kumar Portfolio

Responsive React + Vite portfolio with CSS-only 3D-inspired hover states, floating UI cards, animated portrait frame, and custom project UI mockups. No icon package is required.

## Run locally
1. Install Node.js (LTS) if not already installed.
2. Open this folder in VS Code.
3. In the terminal run:
   ```bash
   npm install
   npm run dev
   ```
4. Open the local URL shown by Vite.

## Personalize
- Replace `public/images/gangesh-profile.png` with your approved portrait PNG (keep the same filename).
- Project links and content are in `src/App.jsx`.
- The contact form opens the visitor's email app; it does not send mail through a backend.
- Resume button has been removed as requested. It can be added later if needed.
- “Live demo coming soon” is intentionally not a fake demo link.

## Build for deployment
```bash
npm run build
```
Upload the folder to GitHub and import the repo into Vercel, using `npm run build` and `dist` as the output directory.
