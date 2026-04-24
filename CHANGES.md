# v0.3.2

Time to bump a number

- Split some code in a new file for better readability
- Fidddled with card sizes, spacings and alignments
- Found one more dialog to style > PlaybackInfo
- Tried something with that off looking counter in the NextUp dialog


# v0.3.1

Main focus on dialogs & list view

- Matched style, positioning and animation speed of different dialogs
- More full-screen dialogs shown in TV mode
- New multi-select style in Desktop mode
- Some mouse cursor adjustments
- New episode list style (list view generally)
- Fixed some alignment and style errors


There is now a transparent box behind the user-settings list, to disable it:

```css
:root {
    [...]
    --itembg: none;
}
```

> This variable could be used to style more elements in feature updates


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
