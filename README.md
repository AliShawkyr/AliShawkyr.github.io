# Ali Shawki — Personal Portfolio

A responsive, English-language portfolio website for a Senior Test Engineer.

## Preview locally
Open `index.html` in a browser. An internet connection is needed for the Google Fonts.

## Personalize before publishing
1. Replace the illustrated portrait in the hero section with your own professional photo in a suit.
   - Save your image as `assets/ali-shawki.jpg`.
   - In `index.html`, replace the `<div class="portrait-placeholder"> ... </div>` block with:
     `<img class="portrait-photo" src="assets/ali-shawki.jpg" alt="Ali Shawki, Senior Test Engineer">`
   - Add this to `style.css`:
     `.portrait-photo { width:100%; height:100%; object-fit:cover; border-radius:135px 135px 24px 24px; }`
2. Replace the LinkedIn link with your profile URL.
3. Replace `your.email@example.com` with your professional email.
4. Add a PDF CV link if you want a downloadable resume button.
5. Review the wording and add only tools/skills you can confidently discuss in an interview.

## Publish for free with GitHub Pages
1. Create a GitHub repository named `YOUR-USERNAME.github.io`.
2. Upload the files and the `assets` folder.
3. Open repository **Settings → Pages** and select deployment from the `main` branch / root folder.
4. Your site will be published at `https://YOUR-USERNAME.github.io`.

The portfolio includes a generated professional portrait at `assets/ali-shawki.png`. Replace it with your preferred original photo if needed.
