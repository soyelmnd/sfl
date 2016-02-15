# SFL


## Isn't SFL another Simple Flex Layout?
Indeed, it's a dead simple and flexible flex grid, but not a whole new one. It's
originally a mimic of the handy layout system shipped with the Google's mighty
[Angular Material](https://material.angularjs.org/latest/layout/introduction).  

For the definitive how-to-use guide, please refer to the fabulous Angular
Material doc at [https://material.angularjs.org/latest/layout/introduction](https://material.angularjs.org/latest/layout/introduction).
Also, classes could be used instead of attribute values. It's absolutely not
required, just my own preferences :-)

For eg:  
* `layout="row"` should become `class="layout-row`
* `flex="33"` should become `class="flex-33"`
* `layout-align="space-around center"` should become `class="layout-align-space-around-center"`
* `layout-align="center"` should become `class="layout-align-center"`
* `layout-align=" end"` should become `class="layout-align--end"`


## How to install
`bower install sfl`  
TODO


## Sass, less, css, or what?
TODO


## Configurable, why not
TODO


## Showcases
TODO


---


## Errata
There are a few known issues with flex box at the time of writing this:  
* May not work properly with button, fieldset, and table
[https://bugzilla.mozilla.org/show_bug.cgi?id=984869](https://bugzilla.mozilla.org/show_bug.cgi?id=984869)
