# Gowri Shankar A — Portfolio

A responsive portfolio built with plain HTML, CSS, and vanilla JavaScript.

## Run locally
1. Extract the ZIP file.
2. Open `index.html` in your browser.

No build tools or dependencies are required. Google Fonts are loaded online; the page uses fallback fonts if offline.

## Add your photo
Put your photo in the `assets` folder, for example as `profile.jpg`, then in `index.html` change:
`src="assets/profile-placeholder.svg"`
to:
`src="assets/profile.jpg"`
Also update the `alt` text to describe your photo.

## Add projects
In `index.html`, find the `empty-projects` section and replace it with project cards. An example is included in the HTML comment immediately after that section. Only add real projects you have completed.

## Contact form
The form validates required fields and opens the visitor's default email application with the message addressed to `gowrishankar1303@gmail.com`. It does not send directly from the website. To receive submissions without requiring an email app, connect a form backend or form service before publishing.

## Personal details
The page uses `Gowri Shankar A` because that was the supplied display name. Update the title, heading, and metadata if you want the site to display a different name.
