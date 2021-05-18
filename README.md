# simpleJson
A simple jQuery plugin to render collapsible Json

## Structure
There are 3 parts to the plugin:

javascript
css
image file
To use the plugin, simply include the above 3 files into your project (note that based off where the image file is put on your site, it might be necessary to update the CSS file accordingly) and ensure that the javascript file is included after jQuery has been added (pretty much any version of jQuery will do).

To use the plugin, then the following can be used:

```
var o = { "property1": "value1", "array": [1,2,3,5]};
$(“#simpleUseCase”).empty().simpleJson({ jsonObject: o });
```

## Options

The following options are available:

| Property | Description | Required |
| --- | --- | --- |
| jsonObject | The object which should be rendered | Y |
| collapsedText | The text which should be shown whilst an object has been collapsed (Defaults to '...') | N |

## FAQs

### Can I use in this my project etc.?
Yes. Please do. The only thing that we ask (and you don't have to do so) is that you let us know if it's proved useful for you. That motivates us to keep providing components.

### I want to update the look and feel of the expanders etc. How do I do so?
All of this is controlled by standard css and the image file. Make any changes there and they'll be reflected.

### I have a suggestion, what do I do?
Contact us @ simpleJson@borsuksoftware.co.uk or create an issue above.
