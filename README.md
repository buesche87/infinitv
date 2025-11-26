This theme was created with a focus on HTPCs. 

- Minimalist design
- Remote control operation
- Custom accent color and transparency
- Custom background image

Optimal results:
- *use the newest jellyfin media player built with qt6-webengine*
- Set theme to `Dark`
- Set display mode to `TV`
- Activate backdrops

Give it *your* accent by changing `:root` values:
- `accent-h: 36` > use the `L` value from a HSL-color picker
- Set your background image with `bgImage: url("https://url.to/picture.jpg")`
- set background darkness from `0.00` to `1.00`
- set opacity from `1.00` to `0.00`
- give roundings more radius


This is a hobby project to expand my basic knowledge of CSS. Therefore, it does not claim to be complete or bug-free. Ideas and problems will be addressed when free time allows.


---

Add the following to your custom branding:

```css
/* Add to Custom CSS in Dashboard > Branding */
@import url('https://buesche87.github.io/infinitv/infinitv.css');
@import url('https://buesche87.github.io/infinitv/infinitv-cast.css');
:root {

  /* Accent Color */
  --accent-h: 36;    /* Hue: Orange */
  --accent-s: 100%;  /* Saturation */
  --accent-l: 50%;   /* Brightness */

  /* Background Image */
  --bgImage: url("https://wallpapershome.com/images/pages/pic_h/12740.jpg");

  /* Darkness & Opacity */
  --bgdarkness: 0.6;    /* Background Darkness */
  --headeropacity: 0.7; /* Header Opacity */
  --draweropacity: 0.9; /* Drawer Opacity */
  --footeropacity: 0.8; /* Card Footer Opacity */

  /* Roundings */
  --rounding-media: 12px;
  --rounding-system: 4px;
}
```

# Screenshots

<img width="1946" height="1103" alt="home_focused" src="https://github.com/user-attachments/assets/8e61244a-38e7-49f2-b6c6-5cbdd2dc03a8" />
<img width="1954" height="1112" alt="poster_cards_focus" src="https://github.com/user-attachments/assets/0bc4337c-ce95-45d1-985a-081cfdd15388" />
<img width="1964" height="1116" alt="series" src="https://github.com/user-attachments/assets/dbaff509-a708-4e26-9a0b-52cc804288d0" />
<img width="1935" height="1096" alt="seasons_focused" src="https://github.com/user-attachments/assets/2d548971-aa17-4f6a-9f2c-3e327a203f3a" />
<img width="1952" height="1016" alt="player" src="https://github.com/user-attachments/assets/bd4afc57-9031-4226-b650-8626dfafcdcd" />
<img width="1944" height="1104" alt="movie_backdrops" src="https://github.com/user-attachments/assets/78d2378b-17e1-4a13-895c-9352a6d293b8" />
<img width="1939" height="1098" alt="userprofile_focused" src="https://github.com/user-attachments/assets/879e1aff-f2a1-4c0b-bd91-e04fee03a07d" />

## Different Accents
<img width="1951" height="1110" alt="home_cyan" src="https://github.com/user-attachments/assets/bd2a1238-508c-43aa-95ca-ca4fa6c5b3e9" />

