PHILOSOPHY QUIZ WEBSITE — GITHUB PAGES

FILES
- index.html: the interactive scrolling quiz
- page1.jpg through page10.jpg: the original PDF pages used as backgrounds

PUBLISH
1. Create a PUBLIC GitHub repository.
2. Upload index.html and all ten page*.jpg files into the repository root (not inside a subfolder).
3. Open Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch.
5. Select branch main and folder /(root), then Save.
6. Wait for GitHub Pages to publish. Your URL will look like:
   https://YOUR-USERNAME.github.io/REPOSITORY-NAME/

MIT APP INVENTOR
Set your WebViewer's HomeUrl to that published URL.

NOTES
- The green guide area is not shown as a green box; the answer textareas are white and positioned over that area.
- Answers save in the browser's local storage on that device/browser. Users should download their answers before clearing browser data or switching devices.
- PDF export uses jsPDF from a CDN, so internet access is needed when exporting.
- This is a static website; it does not send answers to you or a server.
