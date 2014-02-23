bootstrap-slider [![Build Status](https://travis-ci.org/seiyria/bootstrap-slider.png?branch=master)](https://travis-ci.org/seiyria/bootstrap-slider)
================
A "fork" of bootstrap-slider found on http://www.eyecon.ro/ originally by Stefan Petre.

Want to use this with Rails? [Check it out!](https://github.com/stationkeeping/bootstrap-slider-rails)

Installation
============
Clone the repository, then run `npm install`

Examples
========
You can see all of our API examples [here](http://seiyria.github.io/bootstrap-slider/).

Using bootstrap-slider
======================

Create an input element and call .slider() on it:

```js
$("input.slider").slider();
```

Options
=======
Options can be passed either as a data (data-slider-foo) attribute, or as part of an object in the slider call. The only exception here is the formater argument - that can not be passed as a data- attribute.


| Name | Type |	Default |	Description |
| ---- |:----:|:-------:|:----------- |
| id | string | '' | set the id of the slider element when it's created |
| min |	float	| 0 |	minimum possible value |
| max |	float |	10 |	maximum possible value | 
| step | float |	1 |	increment step |
| orientation |	string | 'horizontal' |	set the orientation. Accepts 'vertical' or 'horizontal' |
| value |	float,array |	5	| initial value. Use array to have a range slider. |
| selection |	string |	'before' |	selection placement. Accepts: 'before', 'after' or 'none'. In case of a range slider, the selection will be placed between the handles |
| tooltip |	string |	'show' |	whether to show the tooltip on drag, hide the tooltip, or always show the tooltip. Accepts: 'show', 'hide', or 'always' |
| handle |	string |	'round' |	handle shape. Accepts: 'round', 'square' or 'triangle' |
| reversed | bool | false | whether or not the slider should be reversed |
| enabled | bool | true | whether or not the slider is initially enabled |
| formater |	function |	returns the plain value |	formatter callback. Return the value wanted to be displayed in the tooltip |

Functions
=========
| Function | Description |
| -------- | ----------- |
| .slider(options) | Initializes the slider |
| .slider('getValue') | Get the current value from the slider |
| .slider('setValue', newValue) | Set a new value for the slider |
| .slider('destroy') | Properly clean up and remove the slider instance |
| .slider('disable') | Disables the slider and prevents the user from changing the value |
| .slider('enable') | Enables the slider |
| .slider('toggle') | Toggles the slider between enabled and disabled |
| .slider('isEnabled') | Returns true if enabled, false if disabled |

Events
======
| Event | Description |
| ----- | ----------- |
| slideStart | This event fires when dragging starts |
| slide | This event fires when the slider is dragged |
| slideStop | This event fires when the dragging stops |
| slideChange | This event fires when the slider value changes via slider.setValue() |
| slideEnabled | This event fires when the slider is enabled |
| slideDisabled | This event fires when the slider is disabled |


### Recommend extensions

- [Bootstrap Ajax Typeahead Plugin](https://github.com/biggora/bootstrap-ajax-typeahead)
- [Bootstrap Fancy File Plugin](https://github.com/biggora/bootstrap-fancyfile/)
- [Bootstrap Select Plugin](https://github.com/biggora/bootstrap-select/)
- [TrinteJS - Javascrpt MVC Framework for Node.JS](http://www.trintejs.com/)
- [CaminteJS - Cross-db ORM for NodeJS](http://www.camintejs.com/)
- [MongoDB Session Storage for ExpressJS](https://github.com/biggora/express-mongodb)
- [Middleware exposing user-agent for NodeJS](https://github.com/biggora/express-useragent)
- [2CO NodeJS adapter for 2checkout API payment gateway](https://github.com/biggora/2co)

Copyright and license
-------
The Apache 2.0 License (Apache)

Copyright (c) 2013-2014 Stefan Petre

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

UNLESS REQUIRED BY APPLICABLE LAW OR AGREED TO IN WRITING, SOFTWARE
DISTRIBUTED UNDER THE LICENSE IS DISTRIBUTED ON AN "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, EITHER EXPRESS OR IMPLIED.
SEE THE LICENSE FOR THE SPECIFIC LANGUAGE GOVERNING PERMISSIONS AND
LIMITATIONS UNDER THE LICENSE.

## Resources

- Visit the [author website](http://www.gordejev.lv).
- Follow [@biggora](https://twitter.com/#!/biggora) on Twitter for updates.
- Report issues on the [github issues](https://github.com/biggora/bootstrap-slider/issues) page.



[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/biggora/bootstrap-slider/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

