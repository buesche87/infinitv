This theme has its focus on HTPCs running jellyfin-desktop as client.

- Minimalist UI optimized for remote and keyboard use
- Customizable accent color, transparency, and background image
- Compact player OSD on sufficiently wide screens
- Custom cards with custom animations
- Centered menus, pages, and titles where appropriate


Optimal results:
- [Jellyfin Desktop v2.0.0](https://github.com/jellyfin/jellyfin-desktop/releases)
- Set theme to `Dark`
- Set display mode to `TV`


Give it your style by changing `:root` values:
- `accent-h: 310` > use the `H` value from an HSL-color picker
- Set your wallpaper with `bgImage: url("https://url.to/picture.jpg")`
- set background darkness from `0.00` to `1.00`
- set opacity from `1.00` to `0.00`
- give roundings more radius


> *This is a hobby project to expand my basic knowledge of CSS. Therefore, it does not claim to be complete or bug-free. Ideas and problems will be addressed when free time allows.*
---


Add the following to your custom branding:

```css
/* Add to Custom CSS in Dashboard > Branding */
@import url('https://buesche87.github.io/infinitv/infinitv.css');
:root {

  /* Accent Color */
  --accent-h: 310;   /* Hue: Purple */
  --accent-s: 100%;  /* Saturation */
  --accent-l: 50%;   /* Brightness */

  /* Background Image */
  --bgImage: url("https://wallpaperaccess.com/download/purple-galaxy-439751");

  /* Darkness & Opacity */
  --bgdarkness:    0.6; /* Background Darkness */
  --headeropacity: 0.7; /* Header & Drawer Opacity */
  --itemopacity:   0.8; /* Item Opacity (Card Footer, Detail Ribbon) */

  /* Roundings */
  --rounding-media: 12px;
  --rounding-system: 6px;
}
```

# Screenshots
<img width="1944" height="1105" alt="home_focused" src="https://github.com/user-attachments/assets/280f081f-3475-4de1-82d8-133c62b229db" />
<img width="1954" height="1112" alt="poster_cards_focus" src="https://github.com/user-attachments/assets/0bc4337c-ce95-45d1-985a-081cfdd15388" />
<img width="1964" height="1116" alt="series" src="https://github.com/user-attachments/assets/dbaff509-a708-4e26-9a0b-52cc804288d0" />
<img width="1935" height="1096" alt="seasons_focused" src="https://github.com/user-attachments/assets/2d548971-aa17-4f6a-9f2c-3e327a203f3a" />
<img width="1952" height="1016" alt="player" src="https://github.com/user-attachments/assets/bd4afc57-9031-4226-b650-8626dfafcdcd" />
<img width="1944" height="1104" alt="movie_backdrops" src="https://github.com/user-attachments/assets/78d2378b-17e1-4a13-895c-9352a6d293b8" />
<img width="1939" height="1098" alt="userprofile_focused" src="https://github.com/user-attachments/assets/879e1aff-f2a1-4c0b-bd91-e04fee03a07d" />

## Different Accents
<img width="1948" height="1107" alt="home_purple" src="https://github.com/user-attachments/assets/a54df518-e033-43fa-a8d0-08c2505ddd5b" />
<img width="1947" height="1104" alt="episodes_cyan" src="https://github.com/user-attachments/assets/62bb20bb-a5d3-4fd0-a6d1-0f226d9861e1" />
