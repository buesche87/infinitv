This theme was created with a focus on HTPCs. 

- Minimalist design
- Remote control operation
- Custom accent color and transparency
- Custom background image

Optimal results:
- Set theme to `Dark`
- Set display mode to `TV`
- Activate backdrops

This is a hobby project to expand my basic knowledge of CSS. Therefore, it does not claim to be complete or bug-free. Ideas and problems will be addressed when free time allows.

Add the following to your custom branding:

```css
/* Add to Custom CSS in Dashboard > Branding */
@import url('https://buesche87.github.io/infinitv/infinitv.css');
@import url('https://buesche87.github.io/infinitv/infinitv-cast.css');
@import url('https://buesche87.github.io/infinitv/ultrachromic-episodes.css');
:root {

  /* Accent Color */
  --accent-h: 36;    /* Hue: Orange */
  --accent-s: 100%;  /* Saturation */
  --accent-l: 50%;   /* Brightness */

  /* Background Image */
  /* > There are limitations when using jellyfin media player */
  /* > the chromium version shipped with qt-webengine5 is too old for some rules*/
  --bgImage: url("https://wallpapershome.com/images/pages/pic_h/12740.jpg");

  /* Darkness & Opacity */
  --bgdarkness: 0.6;    /* Background Darkness */
  --headeropacity: 0.7; /* Header Opacity */
  --draweropacity: 0.9; /* Drawer Opacity */
  --footeropacity: 0.8; /* Card Footer Opacity */

  /* Roundings */
  --rounding-media: 12px;
  --rounding-system: 4px;

  /* Card Shadow */
  --cardshadow: 4px 4px 10px 5px rgba(0, 0, 0, 0.5);
}
```
