# How to use

To add the comment component to your website you can either use one of our integration libraries or the simple `script` snippet.

## Integration libraries

We have a collection of libraries on [Github](https://github.com/komentify/integration-libs) that make integration as easy as possible. Head over there to see the list of supported frameworks / languages.

## Code snippet

The minimal viable configuration is:

```html
<script src="https://www.komentify.io/api/embed" data-app-id="{appId}"></script>
```

The comments component will be inserted into the place you've put this script, right after you replace `{appId}` with the id from your dashboard.

---

If you want more, the structure of the universally usable code snippet is like following:

```html
<script src="https://www.komentify.io/api/embed" 
    data-app-id="{appId}"
    data-selector-id="{elementId}"
    site-selector-id="{siteId}">
</script>
```

Or, alternatively:

```html
<script src="https://www.komentify.io/api/embed?appId={appId}&selectorId={elementId}&siteId={siteId}"></script>
```

The only **required **param is the `{appId}`. Others can be omitted.

Add this script to the end of your `<body>` tag and replace `{appId}` with the id you see in your dashboard.

&nbsp;

`elementId` is the wrapper element that the comment component is placed in.

When omitted, the comment component will be placed where the `<script>` was inserted.

If you want to explicitly specify the element which will contain the comment component, just put the element's `id` in place of `{elementId}`

_Beware_: if you use `elementId` , put the script AFTER the element you want to insert it in, otherwise the `script` will not be able to find it.

&nbsp;

It is also possible to specify a `siteId` parameter that defines the current site that contains the comment component. This is useful if you have a lot of pages that should contain the same comment component but have different URLs.

## Custom Styling

You can already define the main color of your comment widget in the backend, but for more advanced use cases it's possible to add [CSS](http://wtfhtmlcss.com/).

It is possible to customize the appearance of your comment widget by doing following:

* Adding a URL to your stylesheet \(CSS URL\)
* Putting the css into the text box \(CSS\)
* Doing both



