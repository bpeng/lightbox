### Notes for updating bootstrap v5
(20/9/2021)

#### The issue:
- Current version (5.3.0) of `ekko-lightbox` doesn't work **Boostrap** version 5.

####  The changes
- Changes have been made to `ekko-lightbox.js` to resolve the issue.
- **Grunt** tool no longer work to build commonjs from node modules,  so updated `dist/ekko-lightbox.js`, and use `npm minify` to build `dist/ekko-lightbox.min.js`
- Small css update also needed for the close button.
