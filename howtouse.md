# How to use

To add the comment component to your app you can either use one of our integration libraries or the simple `script` snippet. 

## Integration libraries

We have a collection of libraries on [Github](https://github.com/komentify/integration-libs) that make integration as easy as possible. Head over there to see which frameworks / languages are supported.

## Code snippet

The structure of the universally usable code snippet is like following:

```html
<script src="http://www.komentify.io/api/embed?appId={appId}&selectorId={elementId}"></script>
```

Add this script to the end of your `<body>` tag and replace `{appId}` with the id you see in your dashboard. `elementId` is the wrapper element that the comment component should be placed in.

It is also possible to specify a `siteId` parameter that defines the current site that contains the comment component. This is useful if you have a lot of pages that should contain the same comment component but have different URLs.
