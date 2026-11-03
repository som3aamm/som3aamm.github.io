# Ismail Mohamed — Personal Portfolio

A bilingual (English / Arabic), responsive, static portfolio showcasing selected software engineering, SaaS, ERP, AI, automation and research projects.

## Quick start

Open `index.html` directly in a browser. For reliable local preview and testing, run:

```bash
python -m http.server 8080
```

Then visit `http://localhost:8080`.

No `npm install`, API keys, database, or backend is required. The site uses local optimized WebP screenshots, plain HTML/CSS/JavaScript and optional Google Fonts.

## Publish for free

### GitHub Pages

1. Create a new public repository such as `ismail-portfolio` in your own account.
2. Upload the **contents** of this folder (`index.html`, `styles.css`, `script.js`, `assets/`, etc.) to the repository root.
3. Go to **Settings → Pages → Build and deployment** and choose **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. Wait for GitHub Pages to publish and use the URL shown in Pages settings.

Alternatively deploy the folder to Netlify or Cloudflare Pages as a static site. No server-side configuration is necessary.

## Editing projects

Edit the `projects` array in `script.js` to change names, descriptions, tags, galleries, and live links. Add new `.webp` images under `assets/` and set a project's `img` or `gallery` entries to the filename without `.webp`.

## Adding your portrait

The hero currently uses actual project screenshots and the About section uses an `IM.` monogram. A portrait is completely optional: replace the monogram block in `index.html` or add an image in that section when ready.

## Contacts

- Email: `esmailmo522@gmail.com`
- WhatsApp: `+20 121 243 2668`
- GitHub: `https://github.com/som3aamm`

## Privacy and production checklist

- Review every screenshot for client information, credentials, names, or personally identifiable data before publishing. Some content has been reproduced from user-provided screenshots; you are responsible for publication permission.
- Confirm client permission to publicly name projects, display branding, or publish demos/case studies.
- Only the Tarbiyah Hub public case-study and official platform URL have been linked where available. Request access for other live demos rather than publishing private admin login pages.
- Add your custom domain and update the Open Graph URL/image metadata for final deployment.
- This template does not collect personal data or submit contact forms; email and WhatsApp buttons open those services.
