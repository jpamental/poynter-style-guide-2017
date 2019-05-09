# poynter-style-guide-2017

Style Guide from the Poynter Digital Design Challenge 2017. Typecast template by John Martins. Typography by Jeffrey Zeldman. Code cleanup by Noël Jackson. A studio.zeldman.com contribution to the cause. Support #realnews.

## Updated sample style guide with variable fonts and responsive typogrpahy

The purpose of this demo is to show how, when a browser supports variable fonts, you can become much more responsive to the user's device size. This will scale the typography along size, line-height, weight, and optical size axes to give a more appropriate reading experience on a wider range of devices.

I have endeavored to keep the original design and typography intact, but have scoped all of the new typography within an `@supports` block so that the new typography will only be rendered by browsers that will understand what to do with variable fonts.

View it here: https://jpamental.github.io/poynter-style-guide-2017/

## Setup

This repository does use Gulp to compile the Sass, but it is not a requirement to use it. The compiled CSS is also included.

## A note about fonts

IBM Plex Sans Variable has been included. You can find the full IBM Plex family and licensing information here: https://github.com/ibm/plex

Roslindale is a variable font designed by David Jonathan Ross. To use it in your projects, you can purchase a license from him directly here: 
https://djr.com/roslindale/

Or have loads more fun and sign up for his Font of the Month Club: 
https://fontofthemonth.com
