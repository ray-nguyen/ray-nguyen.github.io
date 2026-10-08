# Ray Nguyen — Connect the dots

An interactive marketing portfolio with an editorial charcoal, cream and lime design.

## Explore

- A draggable, keyboard-controlled 3D sculpture with Brand, Digital and Systems modes.
- Scroll reveals, animated results, a moving typography strip and a sticky career introduction.
- Expandable career chapters and a six-part capability map linking to relevant experience.
- Responsive phone layouts, keyboard controls, reduced-motion support and a persistent pause button.
- A public CV with viewing and download links: https://ray-nguyen.github.io/Ray-Nguyen-Resume.pdf.

Career content is based on Ray's supplied October 2026 CV. The PDF is the original supplied file.

## Edit and publish

The repository's index.html is the self-contained publishing build, including Inter, Three.js and GSAP. The PDF remains a separate file at the same level.

Extract ray-nguyen-portfolio-source.zip to edit index.html, styles.css and main.js. No package installation is required. Run:

    node scripts/serve.mjs
    node scripts/build-standalone.mjs

The preview server runs at http://127.0.0.1:4173. The build writes the deployment files to publish/. Upload those files to the repository root and update the source archive after source changes. Replace Ray-Nguyen-Resume.pdf in both the source and the repository when updating the CV.

Repository: https://github.com/ray-nguyen/ray-nguyen.github.io
GitHub Pages: master branch, root folder.

## Behaviour and access

Career chapters use native details controls and remain readable without JavaScript. The sculpture has a static fallback when WebGL is unavailable. System reduced-motion preferences pause animation by default, and visitors can toggle motion explicitly. Animation rendering stops while the sculpture is off screen or the tab is hidden.

Contact messages use FormSubmit to reach raynguyen.marketer@gmail.com. The owner must activate the service using its confirmation email after the first live submission. A successful response confirms acceptance by FormSubmit, not inbox delivery. No test message was sent during the redesign. The direct email link is also available.

Third-party license files remain in assets/ and vendor/, and the font and Three.js licenses are embedded in the publishing build.
