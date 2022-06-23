Fixed highcharts rounded corners
===============
This plugin is a fork from Highcharts' [Rounded Corners](https://github.com/highcharts/rounded-corners) Plugin,
and it's main purpose is changing the behavior of column's corners when the value is negative, to reverse the top and bottom corners and make the column appear as if it was upside-down.

The contents of the plugin is located in the javascript file
`rounded-corners.js`. 

This plugin is published under the MIT license, and the license document is
included in the repository.

### Usage
The plugin adds four options to the column series object; `borderRadiusTopLeft`,
`borderRadiusTopRight`, `borderRadiusBottomLeft` and `borderRadiusBottomRight`.
If the options are given as numbers, they are interpreted as pixels. If given
as percentage strings, they are percentages of the column width.
