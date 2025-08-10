# Homepage_tweaks
Cusom CSS and other stuff for Homepage (https://github.com/gethomepage/homepage)

<img src="/demo.webp" alt="Demo" width="800">


Edit your `custom.css` with parts that you need.

CSS includes:
 - Background color to tint Safari Tab Bar on iPadOS (Show Color in Tab Bar)
 - Animated starfield overlay (best with darker background)
   - `stars.css` - two layer of stars
   - `fog.css` - fog overlay
   - `rocket.css` - small rocket flying across the screen
   - `lavalamp.css` - lava lamp like effect
 - Other tweaks to clean up and use more avaliable space on iPad and PC browsers

`custom.css` is with `stars.css` and other tweaks. If you want to add fog and/or rocket then add code from `fog.css` and/or `rocket.css` in to `custom.css`.
`lavalamp.css` and `rocket.css` can't be used at the same time (both are in `body::after`).

Keep in mind that animation is CPU/GPU resource heavy, it will drain battery faster.
