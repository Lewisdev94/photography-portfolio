# Photo Portfolio

A simple portfolio to showcase some of my photographs. Note that the code has been removed from this repo as i did not want it open to the public.


## Live Preview

Site is live [here](https://photography.lewisdev.me ), hosted on my own server.

## Preview

<img width="1437" alt="photo_portfolio_screenshot" src="https://user-images.githubusercontent.com/66197473/115259392-c376b580-a129-11eb-8ed3-cb52c284ac4e.png">

## Technologies

- Wordpress, PHP, HTML, CSS, JavaScript, jQuery, MasonryJS, AOS (Animate on Scroll)

## Current Features

- Desktop and mobile responsive
- Different photo categories
- Hover overlays on desktop
- Modal on click
- About page


## Future Improvements

- Lazy load photographs
- Force focus onto Modal - prevent tabbing in the background
- Use a CMS to serve photos/tags etc (Django?)
-- Dynamic navbar for new categories
- Remove unused Google Fonts
- Clickable button on desktop to show 4xX images as larger 2xX or 1xX images
- Refactor and unbloat CSS - consolidate media queries
- Refactor JS(!)
- Find fix for letter spacing causing a larger than wanted underline (Possibly fine for now but may be an issue if the menu items are pulled in automatically from a CMS)
- Investigate different compression types/ different file loads for thumbnails/modals. Compression is now very aggressive.


## Completed Improvements

### Version 1.0

- Changed black to off-black and white to off-white (27/04/2021)
- Changed Logo letter spacing (21/04/2021)
- Hosting moved to PHP capable provider. (20/04/2021)
- Page indicators restored after PHP change. (20/04/2021)
- Converted to PHP. Nav and footer are now PHP included into each page. (20/04/2021)
- Added meta description (18/04/2021)
- Compressed images for faster page loading. (18/04/2021)
- Added aria-label to hamburger menu button. (18/04/2021)
- Fixed issue where expanding page width while mobile nav is open breaks the site if mobile nav closes due to media query. JS needs a refactor. (17/04/2021)
- Changed modal function. Modal will open on all devices that have hover ability and all devices larger than 649px regardless of hover ability. (17/04/2021)
- Modal can be escaped by clickable space around the image. Close button is focusable with tabbing. (16/04/2021)
- Modal appears in the centre of the screen at the correct aspect ratio with a close button. (16/04/2021)
- Modal will not display on mobile or desktop when the gallery flex is single column - the images are essentially as large as the modal images will be. (15/04/2021)
- Corrected image on about page (14/04/2021)
- All image overlays have correct text (14/04/2021)
- Image containers are now figures with figcaptions and populated alt tags (13/04/2021)
- External links open in new tabs (13/04/2021)
- Added Favicons for multiple devices (11/04/2021)
- Added a Lato font stack (10/04/2021)
- Overlay appears only on devices that can hover (10/04/2021)


## Creators

Built by Lewis Chandler - [Lewisdev94](https://github.com/Lewisdev94)

Designed by Ola
