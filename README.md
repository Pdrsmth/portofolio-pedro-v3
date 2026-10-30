# Pedro Masdy portfolio, Brittany variant

Single-page Astro portfolio, adapted from the Brittany Chiang v4 structure
(Hero, About, Experience, Projects, Certifications, Contact) with Pedro Masdy's
own content. No heavy 3D, no WebGL. This folder is a separate variant only:
it does not touch the live site at pedromasdy.my.id or any existing portfolio
folder, and it is not deployed.

## Run it locally on Windows (PowerShell)

1. Open a NEW PowerShell window (not a window already running a dev server).
   If a dev server is already running in that window, press Ctrl+C first to
   stop it, then continue.
2. Go to the new folder and check you are in it:
   ```powershell
   cd Downloads\brittany-variant
   pwd
   ```
   `pwd` must end in `brittany-variant`. If it does not, you are in the wrong
   folder, so stop and fix the `cd` path before running anything else.
3. Install dependencies (first time only):
   ```powershell
   npm install
   ```
4. Start the dev server:
   ```powershell
   npm run dev
   ```
   Open the address it prints, usually http://localhost:4321.
5. To stop the server, press Ctrl+C in that same PowerShell window.

## Production build and preview

```powershell
npm run build
npm run preview
```

The build output is in `dist/`. `netlify.toml` publishes `dist/` with
`npm run build`, but nothing is deployed from this folder unless you choose
to deploy it yourself.
