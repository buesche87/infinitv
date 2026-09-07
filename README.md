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

- [x] theme designed with a strong focus on htpcs running jellium-desktop as client
- [x] fully supporting desktop and mobile devices with or without backdrops enabled


## Key features

- A minimalist TV-mode UI optimized for remote control and keyboard navigation
- Custom cards with a smoother overall appearance and custom animations
- Consistently centered menus, pages, and titles where appropriate
- Improved use of previously unused screen space, especially in TV mode
- A compact player OSD if spacing allows
- More responsive elements on mobile devices
- Support for userdefined accent-colors, transparency, and background images
- Many additional small and large refinements throughout the UI


## Give it a try

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
  --bgdarkness: 0.6;    /* Background Darkness */
  --headeropacity: 0.7; /* Header & Drawer Opacity */
  --itemopacity: 0.8;   /* Item Opacity (Card Footer, Detail Ribbon) */
  --osdopacity: 0.6;    /* OSD Opacity */

  /* Roundings */
  --rounding-media: 12px; /* Cards and media related stuff */
  --rounding-system: 6px; /* buttons, text fields and you know... */

  /* Glow & Blur (uncomment to enable) */
  /* --cardglow: none; */
  /* --buttonglow: none; */
  /* --blur: none; */
  /* --cardshadow: none; */
  /* --anispeed: 240ms; */
}
```


## Customize

Give it your style by changing `:root` values:
- Accent color: `--accent-h: 310` > use the `H` value from an HSL-color picker
- Set your wallpaper with `--bgImage: url("https://url.to/picture.jpg")`
- Set background darkness from `0.00` to `1.00`
- Set opacity of different elements from `1.00` to `0.00`
- Give border-roundings a diffeent radius
- Remove glow animations (or set them your way)
- Don't blur backgrounds (*current blur effect eats a lot of performance*)
- Remove all card shadows (*will save a little on performance*)
- even set a custom animation speed for dialogs and some menus

## Optimal Results

- [jellium-desktop](https://github.com/andrewrabert/jellium-desktop) or a chromium based client (v105 and later)
- Set `theme` to `Dark`
- HTPC only: Set `display mode` to `TV`
- Use your settings in `:root`
- Optional: Install [IAmParadox27/jellyfin-plugin-home-sections](https://github.com/IAmParadox27/jellyfin-plugin-home-sections)


# TV

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


# Desktop

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


# Mobile

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

*This is an out-of-hand hobby project that was started with the intent to go beyond a basic knowledge of CSS. No agent touched this so far, so no claim for it to be complete or bug-free. The theme will be demanding on your computer's hardware (I'm trying to reduce that). Ideas and problems will be addressed when free time allows.*
