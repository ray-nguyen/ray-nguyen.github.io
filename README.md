# Ray Nguyen — A story in motion

A chronological cinematic portfolio, retaining Ray's original portrait. Five full-screen chapters pair large headlines with photo or video scenes, one sentence of context, an animated topic icon and a key result.

## Motion and media

The website uses native scrolling with sticky scenes, visible image scaling and parallax, sliding text and results, drawn SVG icons and an animated audio waveform. Two locally hosted, silent ten-second clips play only while visible. The header motion control pauses all animation and video. Reduced-motion preferences disable motion by default. Text and photos remain readable without JavaScript, and video posters cover loading or playback failures.

The photographs and footage are illustrative stock imagery, not recordings of Ray's employers, campaigns or projects. This is stated in the site's expandable imagery credits.

Sources:
- Portrait: existing rayavatar.jpg in Ray's repository.
- Workspace: Dell / Unsplash — https://unsplash.com/photos/a-laptop-on-a-table-uifTyG8vUCk
- Packing: Kampus Production / Pexels — https://www.pexels.com/video/a-seller-packing-the-purchase-order-7855154/
- Microphone: Milo Young / Pexels — https://www.pexels.com/photo/black-microphone-with-black-background-5179401/
- Community: Gül Işık / Pexels — https://www.pexels.com/photo/people-sitting-by-a-table-20488466/
- Cooking: Gary Barnes / Pexels — https://www.pexels.com/video/a-man-preparing-food-6247897/
- Licenses: https://www.pexels.com/license/ and https://unsplash.com/license

The two clips were trimmed, cropped and encoded as silent H.264 MP4 loops. The SVG icons were drawn for this website. Inter is bundled with its license.

## Edit and deploy

Extract ray-nguyen-portfolio-source.zip. Edit index.html, styles.css and main.js. No package installation is required.

    node scripts/serve.mjs
    node scripts/build-standalone.mjs

Preview: http://127.0.0.1:4173. The build embeds photos, font, CSS and JavaScript in publish/index.html. Deploy index.html, ray-packing.mp4, ray-kitchen.mp4 and README.md to the repository root. Keep Ray-Nguyen-Resume.pdf there as well, and update the editable source archive after changes.

Live site: https://ray-nguyen.github.io/
Repository: https://github.com/ray-nguyen/ray-nguyen.github.io
GitHub Pages: master branch, root folder.

The latest original CV remains at https://ray-nguyen.github.io/Ray-Nguyen-Resume.pdf. It was not altered by the redesign.

The optional contact form retains FormSubmit and its activation requirement for raynguyen.marketer@gmail.com. A success response confirms provider acceptance, not inbox delivery. No test message was sent during this redesign. Direct email and LinkedIn links are also available.
