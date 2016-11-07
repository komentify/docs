# How to use

To add the comment component to your website you can either use one of our integration libraries or the simple `script` snippet. 

## Integration libraries

We have a collection of libraries on [Github](https://github.com/komentify/integration-libs) that make integration as easy as possible. Head over there to see the list of supported frameworks / languages.

## Code snippet

The structure of the universally usable code snippet is like following:

```html
<script src="http://www.komentify.io/api/embed?appId={appId}&selectorId={elementId}"></script>
```

Add this script to the end of your `<body>` tag and replace `{appId}` with the id you see in your dashboard. `elementId` is the wrapper element that the comment component is placed in.

It is also possible to specify a `siteId` parameter that defines the current site that contains the comment component. This is useful if you have a lot of pages that should contain the same comment component but have different URLs.

## Custom Styling

You can already define the main color of your comment widget in the backend, but for more advanced use cases it's possible to add [CSS](http://wtfhtmlcss.com/).

It is possible to customize the appearance of your comment widget by doing following:

* Adding a URL to your stylesheet (CSS URL)
* Putting the css into the text box (CSS)
* Doing both






