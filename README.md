# My Wardrobe 💛

A retro outfit builder inspired by the computer closet in *Clueless*, with a blue zebra background.

- **Welcome screen:** enter your name, add your photo, then press START
- **Browse:** flip through tops and bottoms with the arrows. BROWSE shuffles a random outfit
- **Dress Me:** see the outfit on you, with a MISMATCH! warning for clashing plaids
- **Bottom bar:** shoes, bottoms, shirts, sweaters, skin tone, hair colour

It's one static file (`index.html`) with no build step and no dependencies.

## Deploy on GitHub Pages

1. Create a new **public** repository on GitHub, for example `my-wardrobe`.
2. Upload the files in this folder (`index.html`, `README.md`, `.nojekyll`):
   - **On the website:** click **Add file → Upload files**, drag them in, then click **Commit changes**.
   - **Or with git:**
     ```bash
     cd my-wardrobe
     git init
     git add .
     git commit -m "My Wardrobe"
     git branch -M main
     git remote add origin https://github.com/YOUR-USERNAME/my-wardrobe.git
     git push -u origin main
     ```
3. In the repo, go to **Settings → Pages**. Under **Build and deployment**, set **Source** to *Deploy from a branch*, choose **main** and **/ (root)**, then click **Save**.
4. After about a minute your site is live at
   `https://YOUR-USERNAME.github.io/my-wardrobe/`

## Notes

- Your name, photo and outfit are saved in your browser on that device only (localStorage). Nothing is uploaded anywhere.
- The pixel fonts load from Google Fonts. Without internet access the page falls back to a plain monospace font.
- To run it locally, just open `index.html` in a browser.
