# Browser-Based Linux Emulator

This repository hosts a client-side x86 emulator that runs entirely in the web browser using WebAssembly via the `v86` library. It allows you to run a lightweight instance of Alpine Linux without installing any software or extensions.

## Features
- Run a full Linux terminal on restricted devices (like school Chromebooks).
- 100% client-side; no backend server or home PC required.
- Fast loading using a lightweight 64MB RAM footprint.

## How to Deploy (Free via GitHub Pages)
1. Create a new repository on GitHub.
2. Upload `index.html` and this `README.md` to the repository.
3. Go to **Settings** > **Pages** in your GitHub repository.
4. Under **Build and deployment**, set the Source to **Deploy from a branch**.
5. Select the `main` (or `master`) branch and click **Save**.
6. GitHub will give you a public URL (e.g., `https://yourusername.github.io/your-repo-name/`). Open that link on your Chromebook to use your emulator.
