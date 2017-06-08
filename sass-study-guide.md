# _Study Guide for Friday's Sass Project_


## Objectives:
* _Stylesheets are organized using partials and easy to understand_
  * _Resources:_
    * _Architecture for a Sass project by Hugo Giraudel on Sitepoint.com.  Hugo uses architecture similar to SMACSS by Jonathan Snook._
    * _SMACSS boiler plate: http:minamarkham.github.io/sassy-starter_
    * _Monday Homework: Structuring your Sass project_

  * _There's no "right" way, but as long as you have your scss partials in their own respective folders and they are imported into your main scss file, which is linked to an output.css file, which you then link into your html header, you should be fine._

* _Nesting is no more than four levels deep_

* _Variables are used effectively_
  * _Resource: Julian's Color Guide Project: https://github.com/julianflood1/colors ._
  * _Example: color variable in color guide project from Monday.  you store a color value in $color variable and then use that variable throughout project.  If you change the value stored in that variable, you can thus change that color throughout your document, including shades, tints, mixes, etc._

* _At least one use of a Sass color function_
  * _Resource: Sass Functions Documentation: http://sass-lang.com/documentation/Sass/Script/Functions.html ._
  * _Examples: lighten(), darken(), mix()._

* _At least one use of @extend_
    * _Example: if you have some small medium and large cards on a website that have different content but have some similar style attributes like background color, padding, etc., you can extend it from the class of the small card, for example, to the medium and large cards._

* _At least one Bourbon @mixin, function, or add-on_
  * _Youtube series: Codecourse: How to make your CSS awesome with Bourbon, Neat, Bitters and Refills!  https://www.youtube.com/watch?v=8ItNE_DX6Cc ._

* _At least one @mixin of your own_

* _Page is responsive (at least one breakpoint) using Sass-style media queries and/or the Neat grid_
  * _Resource: Landon Schropp's 'Write Better Media Queries with Sass' (weekend homework)_

_{Add resources and examples of your own under the appropriate heading.}_
