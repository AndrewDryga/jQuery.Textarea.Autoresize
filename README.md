# jQuery.Textarea.Autoresize #
https://github.com/AndrewDryga/jQuery.Textarea.Autoresize

## About ##
This plugin resizes textarea height to match it's content height.

## Usage ##
```
$('textarea').autoresize(params_object);
```

Params can also be passed via data-api:
```
<textarea data-default-height="min" data-animated="false"></textarea>
```

### Available params: ###
| Param          | Default value     | Description  |
| ------------- |:------------------:|:------------|
| minHeight      | textarea height   | Minimal height for textarea |
| maxHeight      | false (unlimited) |   Maximal height for textarea. If textarea content is bigger than this value, then scrollbar appears. |
| defaultHeight  | false (turned off)        |    Height that will be set to the textarea when it loose focus |
| animation  | true      |    Animation for focus loose/restore (works only with non-false defaultHeight values) |
| animationDuration  | 'slow'      |    A string or number determining how long the animation will run. |
| animationEasing  | 'swing'      |    Callback function, called each time plugin resizes textarea |
| onResize  | $.noop      |    Callback function, called on each time plugin resizes the textarea |

## Author
[Andrew Dryga](http://dryga.com/)

## License
MIT (Look into LICENSE.md file)
