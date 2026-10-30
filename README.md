# Squash × AI project website

A responsive, static website for documenting the AI-assisted squash officiating project.

## Preview locally
Open `index.html` in a browser.

## Update prototypes
Edit `prototypes.js`. Add another object to the `prototypes` array:
- `number`
- `title`
- `status`
- `description`
- `date`

Save and refresh the page. The cards update automatically.

## Publish publicly with GitHub Pages
1. Create a new GitHub repository. Do not include private data, personal contact details, or raw match footage unless you have permission to publish it.
2. Upload all five website files to the repository's root.
3. In repository Settings → Pages, choose deploy from the `main` branch and `/ (root)`.
4. Save. GitHub Pages will provide a public website address.

This is a static site; no server or database is required. Google Fonts are loaded externally, but the site otherwise uses local files.

## Accuracy note
The 4/9 figure is the small leave-one-out text baseline using clip notes. It is not the accuracy of the YOLO vision model. The site intentionally describes all current results as experimental.
