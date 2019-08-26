Copyright and kudos go to shimmer project maintainers: https://github.com/shimmerproject/Greybird.

Original README: https://github.com/shimmerproject/Greybird/blob/master/README.md



GreybirdX2
=======
Scalable version of [Greybird](https://github.com/shimmerproject/Greybird).
Adds an option to scale GTK3 part of the theme when you feel decorations are too large. Be warned that scale might break all the pixel accuracy efforts made by Greybird maintainers.

Use cases:

* UHD (4,5k,retina) screen with large diagonal: set display scale to 2 and scale down theme and fonts (x0.9)
* to fight blurry xwayland in swaywm: set display scale to 1 and scale up the theme and fonts (1.75)

Howto:

1) `${EDITOR:-vi} gtk-3.0/_common.scss`
2) localte `-px` function
3) set scale
4) build the theme as [original README](https://github.com/shimmerproject/Greybird/blob/master/README.md) tells to
5) Your theme is called `GreybirdX2`