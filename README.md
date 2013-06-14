# jQuery.Textarea.Autoresize #
https://github.com/AndrewDryga/jQuery.Textarea.Autoresize

This plugin resizes textarea height to match it's content height.

## Usage ##
<code>$('textarea').autoresize(params_object);</code>

Params can also be passed via data-api:
<code><textarea data-default-height="min" data-animated="false"></textarea></code>

Available params:
- minHeight: minimal height for textarea, default is textarea height.
- maxHeight: maximal height for textarea, default is false (unlimited). If textarea content is bigger than this value, then scrollbar appears.
- defaultHeight: height that will be set to textarea when it loose focus. Default if false (turned off).
- animated: animation for focus loose/restore (works only width non-false defaultHeight values). Default is true.
- onResize: callback function, called each time plugin resizes textarea.

## Author ## 
Andrew Dryga <andrew@dryga.com> <http://dryga.com>

## License ## 
MIT
