# श्री कान्हा टेंट हाउस — Website

A responsive static website for Shri Kanha Tent House, Amjhera, Madhya Pradesh.

## Files
- `index.html` — site content, Hindi text, SEO metadata, Netlify booking form
- `style.css` — responsive styling
- `script.js` — mobile navigation and footer year
- `netlify.toml` — optional Netlify configuration

## Publish with Netlify (beginner-friendly)
1. Extract `shri_kanha_tent_house_website.zip` on your computer.
2. Open https://app.netlify.com/ and sign in or create an account.
3. From the Netlify dashboard, choose **Add new site** / **Deploy manually** (wording may vary).
4. Drag the extracted website folder (the folder containing `index.html`) into the deploy area. If Netlify requests files instead, drag the contents of the folder.
5. Wait for deployment. Netlify will provide a public `*.netlify.app` URL.

## Publish using GitHub
1. Sign in at https://github.com/ and create a new repository, e.g. `shri-kanha-tent-house`.
2. Upload `index.html`, `style.css`, `script.js`, `netlify.toml`, and this README to the repository root.
3. To host on GitHub Pages: repository **Settings → Pages → Deploy from a branch → main → /(root) → Save**.
4. Or connect that repository to Netlify for easy redeployment on each GitHub update.

## Booking form setup
The form is marked for Netlify Forms (`data-netlify="true"`). Deploy the site to Netlify, then check **Forms** in the Netlify site dashboard. If the form does not appear, enable form detection in the site's settings and redeploy. Test the form after deployment. GitHub Pages alone does not process Netlify Forms; use Netlify if you want this form to collect submissions.

## Important before going live
- Check all phone numbers and the location spelling with the business owner.
- The primary contact is **Shivam Meda — 8878975411**. Alternate number: **9691229392**. Manager: **Chintu Mavi — 8103272364**.
- Gallery photos are sample remote images from Unsplash, not verified photos of the business. Replace them with the tent house's real event photos for best trust and SEO.
- The site uses Google Fonts and sample gallery images from external URLs, so those need an internet connection.
- No pricing or customer reviews are invented. Add only confirmed details.
