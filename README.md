```diff
   ___  ________   ________ ___  ________   ___  _________  ___      ___   
  |\  \|\   ___  \|\  _____\\  \|\   ___  \|\  \|\___   ___\\  \    /  /|   
  \ \  \ \  \\ \  \ \  \__/\ \  \ \  \\ \  \ \  \|___ \  \_\ \  \  /  / /  
   \ \  \ \  \\ \  \ \   __\\ \  \ \  \\ \  \ \  \   \ \  \ \ \  \/  / /   
    \ \  \ \  \\ \  \ \  \_| \ \  \ \  \\ \  \ \  \   \ \  \ \ \    / /    
     \ \__\ \__\\ \__\ \__\   \ \__\ \__\\ \__\ \__\   \ \__\ \ \__/ /     
      \|__|\|__| \|__|\|__|    \|__|\|__| \|__|\|__|    \|__|  \|__|/      
                                                                           
                                                                           
                        The Big Screen Experience                          
```

> This theme is designed with a strong focus on htpc setups using Jellyfin Desktop as the client, while fully supporting both desktop and mobile devices.

## Key features

- A minimalist TV-mode UI optimized for remote control and keyboard navigation
- A redesigned mobile interface placing key elements within easy thumb reach
- Custom cards with a smoother overall appearance and custom animations
- Consistently centered menus, pages, and titles where appropriate
- Improved use of previously unused screen space, especially in TV mode
- A new, compact player OSD on sufficiently wide displays
- Full support for user-defined colors, transparency, and background images
- Many additional small and large refinements throughout the UI

Give it a try!

## Apply

Add the following to your custom branding

```css
@import url('https://buesche87.github.io/infinitv/infinitv.css');
:root {

  /* Accent Color */
  --accent-h: 310;       /* Hue: Purple */
  --accent-s: 100%;      /* Saturation */
  --accent-l: 50%;       /* Brightness */

  /* Background Image */
  --bgImage: url("https://wallpaperaccess.com/download/purple-galaxy-439751");

  /* Darkness & Opacity */
  --bgdarkness:    0.6;  /* Background Darkness */
  --headeropacity: 0.7;  /* Header & Drawer Opacity */
  --itemopacity:   0.8;  /* Item Opacity (Card Footer, Detail Ribbon) */

  /* Roundings */
  --rounding-media: 12px;
  --rounding-system: 6px;

  /* Glow (uncomment to remove glow animations) */
  /* --cardglow: none; */
  /* --buttonglow: none; */

  /* Uncomment to disable user-settings background*/
  /* --itembg: none; */
}
```

## Customize

Give it your style by changing `:root` values:
- Accent color: `--accent-h: 310` > use the `H` value from an HSL-color picker
- Set your wallpaper with `--bgImage: url("https://url.to/picture.jpg")`
- Set background darkness from `0.00` to `1.00`
- Set opacity from `1.00` to `0.00`
- Give roundings more radius


## Optimal Results

- Chromium based client (v105 and later)
- Set `theme` to `Dark`
- Set `display mode` to `TV` (htpc only)
- Use the home sections plugin from [IAmParadox27/jellyfin-plugin-home-sections](https://github.com/IAmParadox27/jellyfin-plugin-home-sections) (optional)

# TV-Mode Screenshots

<table>
  <tr>
    <td><img src="https://raw.githubusercontent.com/buesche87/infinitv/refs/heads/main/resource/tv-home.png"></td>
    <td><img src="https://raw.githubusercontent.com/buesche87/infinitv/refs/heads/main/resource/tv-library.png"></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/buesche87/infinitv/refs/heads/main/resource/tv-series.png"></td>
    <td><img src="https://raw.githubusercontent.com/buesche87/infinitv/refs/heads/main/resource/tv-episodes.png"></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/buesche87/infinitv/refs/heads/main/resource/tv-movie.png"></td>
    <td><img src="https://raw.githubusercontent.com/buesche87/infinitv/refs/heads/main/resource/tv-player.png"></td>
  </tr>
</table>


# Desktop Screenshots

<table>
  <tr>
    <td><img src="https://raw.githubusercontent.com/buesche87/infinitv/refs/heads/main/resource/desktop-home.png"></td>
    <td><img src="https://raw.githubusercontent.com/buesche87/infinitv/refs/heads/main/resource/desktop-library.png"></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/buesche87/infinitv/refs/heads/main/resource/desktop-series.png"></td>
    <td><img src="https://raw.githubusercontent.com/buesche87/infinitv/refs/heads/main/resource/desktop-episodes.png"></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/buesche87/infinitv/refs/heads/main/resource/desktop-movie.png"></td>
    <td><img src="https://raw.githubusercontent.com/buesche87/infinitv/refs/heads/main/resource/desktop-player.png"></td>
  </tr>
</table>


# Mobile Screenshots

<table>
  <tr>
     <td><img src="https://raw.githubusercontent.com/buesche87/infinitv/refs/heads/main/resource/mobile-home.png"></td>
     <td><img src="https://raw.githubusercontent.com/buesche87/infinitv/refs/heads/main/resource/mobile-library.png"></td>
     <td><img src="https://raw.githubusercontent.com/buesche87/infinitv/refs/heads/main/resource/mobile-settings.png"></td>
  </tr>
  <tr>
     <td><img src="https://raw.githubusercontent.com/buesche87/infinitv/refs/heads/main/resource/mobile-series.png"></td>
     <td><img src="https://raw.githubusercontent.com/buesche87/infinitv/refs/heads/main/resource/mobile-episodes.png"></td>
     <td><img src="https://raw.githubusercontent.com/buesche87/infinitv/refs/heads/main/resource/mobile-movie.png"></td>
  </tr>
</table>


## Disclamer

*This is a hobby project to expand my basic knowledge of CSS. Therefore, it does not claim to be complete or bug-free. Ideas and problems will be addressed when free time allows.*

