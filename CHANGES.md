# v0.3.0

> The changes mostly affect desktop layout

- Fixed hover-animations that got broken with newest jellyfin-desktop release
- Removed some hover animations that looked awful
- Reworked and repositioned actionsheet dialogs (like cast or settings while playing)
- Matched drawer and header animation
- Added the possibility to disable glow animations

To disable glow, add the following to your custom css code:

```css
:root {
    [...]
    --cardglow: none;
    --buttonglow: none;
}
```

# v0.2.3

- Work done on subtitle-sync dialog
- Fixed chapter thumbnail position

# v0.2.2

**This version introduces changes to the mobile layout.**

If you would like to keep the previous mobile layout with the header at the bottom, please import the following CSS:

```css
@import url('https://buesche87.github.io/infinitv/infinitv-mobile.css');
```

### Changelog
- Reworked the image search dialog
- Compacted portrait mode for small mobile phones (now optional)
- Further improved accent usage
- Other smaller and bigger stuff fixed or optimized 
- A lot of cleanup
