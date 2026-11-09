# Cymru Lân — Joseph Pritchett

A responsive Welsh Baccalaureate project website about tackling litter in Newport and Cardiff.

## Files
- `index.html` — website content
- `styles.css` — layout and design
- `script.js` — mobile navigation
- `images/` — put your photographs here

## Publish with GitHub Pages
1. Extract this ZIP file.
2. Upload `index.html`, `styles.css`, `script.js` and the `images` folder directly into the root of your GitHub repository.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then press **Save**.
6. Wait for the deployment to finish. Open the published Pages link.

## Add your own Newport and Cardiff photographs
Create/use the `images` folder in the repository and upload four photographs with these exact filenames:
- `newport-litter.jpg` — a litter-affected place in Newport
- `cardiff-litter.jpg` — a litter-affected place in Cardiff
- `newport-view.jpg` — a general photograph of Newport
- `cardiff-view.jpg` — a general photograph of Cardiff

Then open `index.html`, find the `gallery-grid` section, and replace each `<div class="photo-placeholder...">...</div>` with the corresponding image tag. For example, replace the Newport litter placeholder with:

```html
<img class="gallery-photo" src="images/newport-litter.jpg" alt="Litter in a public area of Newport">
```

Do the same for the other three images, changing the filename and descriptive alt text. Add this CSS rule to the end of `styles.css`:

```css
.gallery-photo {
  display: block;
  width: 100%;
  height: 230px;
  object-fit: cover;
  border-radius: 4px;
}
```

Save/commit the changes to GitHub. GitHub Pages will update automatically.

## Photograph and source advice
- Your own photographs are best evidence of local context and, later, your practical work. Only photograph from safe public places; do not include identifiable people without permission.
- For general city photographs, you can use images from Wikimedia Commons or Unsplash. Check the licence and attribution requirements before using an image, and include a credit in the caption or bibliography.
- Do not stage or imply that a photograph shows your own project activity if it does not. Label general/context images clearly.
- Do not touch litter, needles, chemicals or unknown waste to take a photograph. Keep a safe distance.

## Coursework note
The planning sections are intentions, not claims that the practical work has already happened. Update the schedule and success measures to reflect what you actually do. Add genuine photographs, recorded results and evaluation after the project begins.

## Name
“Cymru Lân” is intended as “Clean Wales” / “A Clean Wales”.
