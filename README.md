# GOVINDA CLASSES (GOVINDA BHIYA) — Website
Owner: SUMIT YADUVANSHI
Location: JNV Road, Fatehgarh, Farrukhabad, Uttar Pradesh

## Pages
- `index.html` — premium homepage and announcements
- `about.html` — institute overview
- `courses.html` — class groups, subjects and fee placeholders
- `materials.html` — public PDF library layout
- `results.html` — reserved for verified results/testimonials
- `gallery.html` — illustrative stock images; replace with actual institute photos
- `contact.html` — admission enquiry form and Google Maps location
- `style.css`, `script.js`, `assets/logo.svg`

## Important setup before publishing
1. Open `contact.html` and replace `YOUR_EMAIL_HERE` in the form action with the institute's real email address, e.g. `https://formsubmit.co/your-real-email@example.com`.
2. Publish the site, submit one test enquiry and complete the confirmation email sent by FormSubmit. Test again to ensure the enquiry reaches the correct inbox. FormSubmit is a third-party service; review its current privacy and terms before use.
3. The form will use FormSubmit’s default confirmation flow after email setup. The current form cannot deliver messages until a valid email is configured and confirmed.
4. Add the official contact phone/email once confirmed.
5. Confirm exact class-wise subject offerings, fees, teacher names and batch timings. The site intentionally does not invent those facts.
6. Add PDFs into the `pdfs/` folder and edit `materials.html` to link each real file. No PDFs were supplied with this version.
7. Replace the illustrative stock photos in `gallery.html` and homepage with real institute photos. The current gallery labels them as illustrative. Get consent before publishing student photos.
8. Add only genuine, verified results and testimonials with permission. No fabricated results or reviews are included.
9. Verify the exact map pin/location. The current Google Maps search uses the address supplied and may be approximate.

## Test locally
Extract the ZIP and open `index.html` in a browser. Internet access is needed for Google Fonts, stock images and the Google Maps embed. Navigation links open pages in the same tab. Mobile navigation is responsive.

## Publish using GitHub + Vercel
1. Create a GitHub repository, e.g. `govinda-classes-website`.
2. Upload the CONTENTS of this folder to the repository root, including `index.html`, other HTML pages, `style.css`, `script.js`, `assets/`, and `pdfs/`.
3. On Vercel choose Add New → Project, import the repository, select Framework Preset `Other`, leave build command blank, and deploy.
4. Test every navigation link, the map, mobile layout, PDFs and a real test enquiry after deployment.

## Privacy and security
There is no student login or admin login. Do not put private student records or confidential PDFs in this public static site. A static public PDF library is visible to anyone with the link. For private materials or a secure staff dashboard, a proper authenticated backend would be needed.
