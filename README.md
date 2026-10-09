# Mayush Tripathi — Portfolio

A responsive, one-page portfolio built with HTML, CSS and JavaScript. It runs directly on GitHub Pages without a build step or external libraries.

## Preview

Open `index.html` in a browser. Keep the `assets/` folder beside it.

## Publish to the existing GitHub Pages site

1. Upload `index.html`, `README.md`, and the complete `assets/` folder to the root of the `mayush-tripathi/portfolio` repository.
2. Commit the uploaded files to the branch used by GitHub Pages.
3. Wait for GitHub Pages to finish deploying, then refresh the portfolio URL.

The image paths are relative, so preserve the `assets/projects/` and `assets/profile/` folders.

## Portfolio contents

- Animated intro, scroll reveals, project filters, image galleries, responsive navigation, and reduced-motion support.
- Profile illustration provided by Mayush.
- CV-based profile, skills, work experience, education, courses, language, and contact details.
- Vintage camera, Willys MB jeep, horse with UV/PBR views, fantasy axe, and nature/street environment video previews.

The project videos load on demand; their full controls appear when a project card is opened. The nature video is stored as two small binary parts so it can be uploaded through GitHub's browser file picker; the page joins them before playback. No M18 Smoke Grenade is included.


## GitHub upload notes

This package keeps the website and image assets separate from large video files so the main site is easier to upload through GitHub's browser interface.

- Upload the contents of this folder (`index.html`, `README.md`, and `assets/`) to the root of your repository.
- Large videos are intentionally not included in this website bundle. They are provided in the separate `portfolio-videos-separate.zip` package.
- If you want videos embedded on the live site, host them on a video/CDN service and update the video sources in `index.html` to the hosted URLs. Do not upload duplicate `.part1`/`.part2` files.
