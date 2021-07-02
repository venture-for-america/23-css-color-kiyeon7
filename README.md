# CSS Color

## Overview

In this lesson we will do a quick review of CSS color propoerties and their accepted values. Both topics were covered in the video lecture in the prior lesson.

## What's Covered in This Lesson 

1. Review CSS Color Names
2. Review CSS Hexidecimal Color Values
3. Review CSS RGB and RGBA Color Values
4. Review CSS HSL and HSLA Color Values

## Colors

### Names

There are 16 cross browser compatible color names: aqua, black, fuchsia, gray (or grey), green, lime, maroon, navy, olive, purple, red, silver, teal, white, and yellow.

### Hexadecimal

There are over 16 million possible color combinations using hex values. Hex values are preceeded by a `#` hashtag symbol and follow with three values back to back listed as numbers 0-9 and letters A-F. The first two characters are for the amount of red, followed by green, and blue. For example with F being the largest amount of a color and 0 being the lowest, the hex color `#FF0000` is the brightest color red. In situations where the three pairs of hex values match as in the last example you can shorten this to: `#F00` instead. Note that this only works for hex values where each of the three pairs match. The hex color `#3345AF` which incidentally is a dark blue color can not be shortened.

### RGB and RGBA

We can produce any color our eye can see using RGB values. These are created by listing a set of numbers for red, green, and blue respectively using a range of 0 the absence of light and 255 the brightest amount of light possible for that color. These values are comma separated, enclosed in parentheses, and preceeded by 'rgb'. For example, `rbg(255,0,0)` is the color red. Using RGBA we supply a fourth number, the alpha value. This is the opacity given in a range of 0-1, where `0` is 0% and `100` is 100% opacity. `rgba(255,0,0,0.5)` is the color red at 50% transparency.

### HSL and HSLA

There are other supported values such as HSL (Hue Saturation Lightness) or HSLA (Hue Saturation, Lightness, Alpha). These are less commonly seen, but if you're interested you can read more about them in the resource links at the end of the lesson.

## Summary

- Colors can be specified using color names, hex, rgb, rgba, hsl, or hsla.

## Resources

- [MDN - CSS Tutorials for Beginners](https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Getting_started)
- [MDN - CSS Property Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)
- [CSS Performance & Organization, Best Practices](http://learn.shayhowe.com/advanced-html-css/performance-organization/)
- [Adobe - Color Scheme Tool](https://color.adobe.com/create/color-wheel/)
- [CSS Tricks - HSLA](https://css-tricks.com/yay-for-hsla/)

<p class='util--hide'>View <a href='https://learn.co/lessons/css-color'>Color</a> on Learn.co and start learning to code for free.</p>
