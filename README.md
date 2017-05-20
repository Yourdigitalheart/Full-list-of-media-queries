# Full list of media queries

```/* ----------- General screens ----------- */

/* ----------- Small screens ----------- */
@media only screen { } /* Define mobile styles */

@media only screen and (max-width: 40em) { } /* max-width 640px, mobile-only styles, use when QAing mobile issues */

/* ----------- Medium screens ----------- */
@media only screen and (min-width: 40.063em) { } /* min-width 641px, medium screens */

@media only screen and (min-width: 40.063em) and (max-width: 64em) { } /* min-width 641px and max-width 1024px, use when QAing tablet-only issues */

/* ----------- Large screens ----------- */
@media only screen and (min-width: 64.063em) { } /* min-width 1025px, large screens */

@media only screen and (min-width: 64.063em) and (max-width: 90em) { } /* min-width 1025px and max-width 1440px, use when QAing large screen-only issues */

/* ----------- XLarge screens ----------- */
@media only screen and (min-width: 90.063em) { } /* min-width 1441px, xlarge screens */

@media only screen and (min-width: 90.063em) and (max-width: 120em) { } /* min-width 1441px and max-width 1920px, use when QAing xlarge screen-only issues */

/* ----------- XXLarge screens ----------- */
@media only screen and (min-width: 120.063em) { } /* min-width 1921px, xxlarge screens */


/* -----------  More  styles ----------- */

/* ----------- Non-Retina Screens ----------- */
@media screen
  and (min-device-width: 1200px)
  and (max-device-width: 1600px)
  and (-webkit-min-device-pixel-ratio: 1) {
}

/* ----------- Retina Screens ----------- */
@media screen
  and (min-device-width: 1200px)
  and (max-device-width: 1600px)
  and (-webkit-min-device-pixel-ratio: 2)
  and (min-resolution: 192dpi) {
}

/* -----------  Mobile screens ----------- */

/* ----------- iPhone 4 and 4S ----------- */

/* Portrait and Landscape */
@media only screen
  and (min-device-width: 320px)
  and (max-device-width: 480px)
  and (-webkit-min-device-pixel-ratio: 2) {

}

/* Portrait */
@media only screen
  and (min-device-width: 320px)
  and (max-device-width: 480px)
  and (-webkit-min-device-pixel-ratio: 2)
  and (orientation: portrait) {
}

/* Landscape */
@media only screen
  and (min-device-width: 320px)
  and (max-device-width: 480px)
  and (-webkit-min-device-pixel-ratio: 2)
  and (orientation: landscape) {

}

/* ----------- iPhone 5 and 5S ----------- */

/* Portrait and Landscape */
@media only screen
  and (min-device-width: 320px)
  and (max-device-width: 568px)
  and (-webkit-min-device-pixel-ratio: 2) {

}

/* Portrait */
@media only screen
  and (min-device-width: 320px)
  and (max-device-width: 568px)
  and (-webkit-min-device-pixel-ratio: 2)
  and (orientation: portrait) {
}

/* Landscape */
@media only screen
  and (min-device-width: 320px)
  and (max-device-width: 568px)
  and (-webkit-min-device-pixel-ratio: 2)
  and (orientation: landscape) {

}

/* ----------- iPhone 6 ----------- */

/* Portrait and Landscape */
@media only screen
  and (min-device-width: 375px)
  and (max-device-width: 667px)
  and (-webkit-min-device-pixel-ratio: 2) {

}

/* Portrait */
@media only screen
  and (min-device-width: 375px)
  and (max-device-width: 667px)
  and (-webkit-min-device-pixel-ratio: 2)
  and (orientation: portrait) {

}

/* Landscape */
@media only screen
  and (min-device-width: 375px)
  and (max-device-width: 667px)
  and (-webkit-min-device-pixel-ratio: 2)
  and (orientation: landscape) {

}

/* ----------- iPhone 6+ ----------- */

/* Portrait and Landscape */
@media only screen
  and (min-device-width: 414px)
  and (max-device-width: 736px)
  and (-webkit-min-device-pixel-ratio: 3) {

}

/* Portrait */
@media only screen
  and (min-device-width: 414px)
  and (max-device-width: 736px)
  and (-webkit-min-device-pixel-ratio: 3)
  and (orientation: portrait) {

}

/* Landscape */
@media only screen
  and (min-device-width: 414px)
  and (max-device-width: 736px)
  and (-webkit-min-device-pixel-ratio: 3)
  and (orientation: landscape) {

}
/* ----------- Galaxy S3 ----------- */

/* Portrait and Landscape */
@media screen
  and (device-width: 320px)
  and (device-height: 640px)
  and (-webkit-device-pixel-ratio: 2) {

}

/* Portrait */
@media screen
  and (device-width: 320px)
  and (device-height: 640px)
  and (-webkit-device-pixel-ratio: 2)
  and (orientation: portrait) {

}

/* Landscape */
@media screen
  and (device-width: 320px)
  and (device-height: 640px)
  and (-webkit-device-pixel-ratio: 2)
  and (orientation: landscape) {

}

/* ----------- Galaxy S4 ----------- */

/* Portrait and Landscape */
@media screen
  and (device-width: 320px)
  and (device-height: 640px)
  and (-webkit-device-pixel-ratio: 3) {

}

/* Portrait */
@media screen
  and (device-width: 320px)
  and (device-height: 640px)
  and (-webkit-device-pixel-ratio: 3)
  and (orientation: portrait) {

}

/* Landscape */
@media screen
  and (device-width: 320px)
  and (device-height: 640px)
  and (-webkit-device-pixel-ratio: 3)
  and (orientation: landscape) {

}

/* ----------- Galaxy S5 ----------- */

/* Portrait and Landscape */
@media screen
  and (device-width: 360px)
  and (device-height: 640px)
  and (-webkit-device-pixel-ratio: 3) {

}

/* Portrait */
@media screen
  and (device-width: 360px)
  and (device-height: 640px)
  and (-webkit-device-pixel-ratio: 3)
  and (orientation: portrait) {

}

/* Landscape */
@media screen
  and (device-width: 360px)
  and (device-height: 640px)
  and (-webkit-device-pixel-ratio: 3)
  and (orientation: landscape) {

}
/* ----------- HTC One ----------- */

/* Portrait and Landscape */
@media screen
  and (device-width: 360px)
  and (device-height: 640px)
  and (-webkit-device-pixel-ratio: 3) {

}

/* Portrait */
@media screen
  and (device-width: 360px)
  and (device-height: 640px)
  and (-webkit-device-pixel-ratio: 3)
  and (orientation: portrait) {

}

/* Landscape */
@media screen
  and (device-width: 360px)
  and (device-height: 640px)
  and (-webkit-device-pixel-ratio: 3)
  and (orientation: landscape) {

}
/* ----------- iPad mini ----------- */

/* Portrait and Landscape */
@media only screen
  and (min-device-width: 768px)
  and (max-device-width: 1024px)
  and (-webkit-min-device-pixel-ratio: 1) {

}

/* Portrait */
@media only screen
  and (min-device-width: 768px)
  and (max-device-width: 1024px)
  and (orientation: portrait)
  and (-webkit-min-device-pixel-ratio: 1) {

}

/* Landscape */
@media only screen
  and (min-device-width: 768px)
  and (max-device-width: 1024px)
  and (orientation: landscape)
  and (-webkit-min-device-pixel-ratio: 1) {

}

/* ----------- iPad 1 and 2 ----------- */
/* Portrait and Landscape */
@media only screen
  and (min-device-width: 768px)
  and (max-device-width: 1024px)
  and (-webkit-min-device-pixel-ratio: 1) {

}

/* Portrait */
@media only screen
  and (min-device-width: 768px)
  and (max-device-width: 1024px)
  and (orientation: portrait)
  and (-webkit-min-device-pixel-ratio: 1) {

}

/* Landscape */
@media only screen
  and (min-device-width: 768px)
  and (max-device-width: 1024px)
  and (orientation: landscape)
  and (-webkit-min-device-pixel-ratio: 1) {

}

/* ----------- iPad 3 and 4 ----------- */
/* Portrait and Landscape */
@media only screen
  and (min-device-width: 768px)
  and (max-device-width: 1024px)
  and (-webkit-min-device-pixel-ratio: 2) {

}

/* Portrait */
@media only screen
  and (min-device-width: 768px)
  and (max-device-width: 1024px)
  and (orientation: portrait)
  and (-webkit-min-device-pixel-ratio: 2) {

}

/* Landscape */
@media only screen
  and (min-device-width: 768px)
  and (max-device-width: 1024px)
  and (orientation: landscape)
  and (-webkit-min-device-pixel-ratio: 2) {

}
/* ----------- Galaxy Tab 10.1 ----------- */

/* Portrait and Landscape */
@media
  (min-device-width: 800px)
  and (max-device-width: 1280px) {

}

/* Portrait */
@media
  (max-device-width: 800px)
  and (orientation: portrait) {

}

/* Landscape */
@media
  (max-device-width: 1280px)
  and (orientation: landscape) {

}
/* ----------- Asus Nexus 7 ----------- */

/* Portrait and Landscape */
@media screen
  and (device-width: 601px)
  and (device-height: 906px)
  and (-webkit-min-device-pixel-ratio: 1.331)
  and (-webkit-max-device-pixel-ratio: 1.332) {

}

/* Portrait */
@media screen
  and (device-width: 601px)
  and (device-height: 906px)
  and (-webkit-min-device-pixel-ratio: 1.331)
  and (-webkit-max-device-pixel-ratio: 1.332)
  and (orientation: portrait) {

}

/* Landscape */
@media screen
  and (device-width: 601px)
  and (device-height: 906px)
  and (-webkit-min-device-pixel-ratio: 1.331)
  and (-webkit-max-device-pixel-ratio: 1.332)
  and (orientation: landscape) {

}

/* ----------- Kindle Fire HD 7" ----------- */

/* Portrait and Landscape */
@media only screen
  and (min-device-width: 800px)
  and (max-device-width: 1280px)
  and (-webkit-min-device-pixel-ratio: 1.5) {

}

/* Portrait */
@media only screen
  and (min-device-width: 800px)
  and (max-device-width: 1280px)
  and (-webkit-min-device-pixel-ratio: 1.5)
  and (orientation: portrait) {
}

/* Landscape */
@media only screen
  and (min-device-width: 800px)
  and (max-device-width: 1280px)
  and (-webkit-min-device-pixel-ratio: 1.5)
  and (orientation: landscape) {

}

/* ----------- Kindle Fire HD 8.9" ----------- */

/* Portrait and Landscape */
@media only screen
  and (min-device-width: 1200px)
  and (max-device-width: 1600px)
  and (-webkit-min-device-pixel-ratio: 1.5) {

}

/* Portrait */
@media only screen
  and (min-device-width: 1200px)
  and (max-device-width: 1600px)
  and (-webkit-min-device-pixel-ratio: 1.5)
  and (orientation: portrait) {
}

/* Landscape */
@media only screen
  and (min-device-width: 1200px)
  and (max-device-width: 1600px)
  and (-webkit-min-device-pixel-ratio: 1.5)
  and (orientation: landscape) {

}
```
