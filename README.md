# SVG flags

SVG flags of countries optimized for web usage.

## Why

As it seems impossible to find a full package of all country flags optimized for the web and keeping their proportions of all flags (no, flags shouldn't be squares or 4x3 rectangles), here is a complete set where the main source is wikipedia.

Most of the packages we found in Internet have defects as :

* not having the good colors or reflecting the design reality;
* not keeping the proportions;
* not really optimized for web usage (size mainly but also the use of ```viewBox``` SVG property);

Now that [all major browsers accept natively the use of SVG](http://caniuse.com/#feat=svg) as picture, it may be an interesting solution to represent flags in this format. 

## Optimization

All flags use the ```viewBox``` SVG property to avoid them to have fixed width and height.

All flags are named with their ISO 3166-1 alpha-2 code.

## Used tools

* [svgo](https://github.com/svg/svgo/)

## Other repositories you might be interested in

### [flag-icon-css](http://lipis.github.io/flag-icon-css/)

Usable via CSS

Flags are in two formats : 1x1 and 4x3, do don't respect the original proportions

They are not really optimized and aren't reflecting the reality of each country flag's original design.

### [flag-icon](https://github.com/stevenrskelton/flag-icon)

Synced with [flag-icon-css](http://lipis.github.io/flag-icon-css/) so have the same problems.

Exports in png and gif formats

### [Flag-Webicons](https://github.com/seanherron/Flag-Webicons)

Does not respect the original design of all flags (compare the [bolivian flag](https://github.com/seanherron/Flag-Webicons/blob/master/flags/bolivia.svg) for example).

Flags are not fully web optimized (look at the code of all flags)
