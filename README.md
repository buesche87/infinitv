This theme is designed with a strong focus on HTPC setups using jellyfin-desktop as the client, while fully supporting both desktop and mobile devices.

Key features include:

- A minimalist TV-mode UI optimized for remote control and keyboard navigation
- A redesigned mobile interface with special attention to portrait mode, placing key elements within easy thumb reach
- Custom cards with a smoother overall appearance and custom animations
- Consistently centered menus, pages, and titles where appropriate
- Improved use of previously unused screen space, especially in TV mode
- A new, compact player OSD on sufficiently wide displays
- Full support for user-defined colors, transparency, and background images
- Many additional small and large refinements throughout the UI

Give it a try!


Optimal results:
- [Jellyfin Desktop v2.0.0](https://github.com/jellyfin/jellyfin-desktop/releases) or a modern webbrowser
- Set theme to `Dark`
- Set display mode to `TV`


Give it your style by changing `:root` values:
- Accent color: `accent-h: 310` > use the `H` value from an HSL-color picker
- Set your wallpaper with `bgImage: url("https://url.to/picture.jpg")`
- Set background darkness from `0.00` to `1.00`
- Set opacity from `1.00` to `0.00`
- Give roundings more radius


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
| | |
:-------------------------:|:-------------------------:
![](https://raw.githubusercontent.com/buesche87/infinitv/refs/heads/main/resource/home-tv.png)  |  ![](https://raw.githubusercontent.com/buesche87/infinitv/refs/heads/main/resource/movie-tv.png)
![](https://raw.githubusercontent.com/buesche87/infinitv/refs/heads/main/resource/movies-tv.png)  |  ![](https://raw.githubusercontent.com/buesche87/infinitv/refs/heads/main/resource/tvshows-tv.png)
![](https://raw.githubusercontent.com/buesche87/infinitv/refs/heads/main/resource/show-tv.png)  |  ![](https://raw.githubusercontent.com/buesche87/infinitv/refs/heads/main/resource/season-tv.png)
![](https://raw.githubusercontent.com/buesche87/infinitv/refs/heads/main/resource/player-tv.png)  |  



| | |
:-------------------------:|:-------------------------:
![](https://raw.githubusercontent.com/buesche87/infinitv/refs/heads/main/resource/menu-mobile.png)  |  ![](https://raw.githubusercontent.com/buesche87/infinitv/refs/heads/main/resource/movies-mobile.png)

