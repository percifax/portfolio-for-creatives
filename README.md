# portfolio-for-creatives

**Cloning a repository, editing code, pushing and creating a fork, connecting to Netlify:**

1. Clone this repository using GitHub Desktop. The URL is https://github.com/jamesdneufeld/portfolio-for-creatives.
2. Edit the code using Visual Studio Code.
3. Push your edited code using GitHub Desktop and create a fork for personal use when prompted.
4. Sign up to [netlify.com](https://www.netlify.com/) using your GitHub credentials.
5. Add/import your GitHub repository to Netlify.
6. Continue customizing the code in Visual Studio Code and push using GitHub Desktop to update your Netlify site.
 
**Easy things to change for beginners:**

- Change the wording in the hero section of the work page.
- Change the colours in style.css using variables.
- Change the fonts to your preferred Google Fonts in style.css.
- Change the social media link addresses.
- Replace the demo words in the footer with your own bio.
- Replace the demo words on a project page with your own project title and project description.

**CSS Structure:**

- The main stylesheet is style.css. There are additional stylesheets for various features that you may want to use.
- The main stylesheet uses CSS variables for colours and fonts. This is a good place to start for beginners.
- The main stylesheet is mobile first. Minor adjustments for large devices can be made at the bottom of the stylesheet.

**Assets Structure and Image Optimization:**

A folder called assets contains demo images and graphics. Create additional folders for each project to keep things organized. Project images should be JPG format and ideally 1500 pixels wide for portrait, 1900 pixels wide for landscape, and under 750 KB. Optimizing images for quick downloading is very important. Do not add huge images or media files as this will slow your site down and could cause technical problems with GitHub. Videos should be uploaded to a third-party like Vimeo or YouTube and then embedded into the HTML code. Animated GIFs should be under 20 frames. Anymore more and it is basically a movie.

## Template Features & Options:

- Big hero area for your branding and intro
- Work page is based on <a href="https://css-tricks.com/snippets/css/complete-guide-grid/" target="_blank">CSS Grid</a> and project preview images size is easily adjustable
- Grayscale filter on project images / full color on hover
- Project page has a sticky sidebar
- Custom cursor
- Make something randomly fly across the screen
- Animated background gradient
- Smooth scroll to top of page
- Show/hide previous/next project button when scrolling down page
- Strokes, shadows + halftone typography effects
- Font Awesome icons included
- CSS custom properties (variables) for easy color scheming
- Instructions in the CSS comments to find things easier
