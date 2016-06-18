# <%= props.name %>
![][bower-badge] [![][travis-badge]][travis-url] [![][bowerdeps-badge]][bowerdeps-url]

<%= props.description %>

### Basic Usage
Install the web components polyfill and <%= props.name %> with bower
```sh
$ bower install webcomponentsjs <%= props.name %> --save
```

Include the webcomponents polyfill and import <%= props.name %> into your project
```html
<script src="/bower_components/webcomponentsjs/webcomponents-lite.js"></script>
<link rel="import" href="/bower_components/<%= props.name %>/<%= props.name %>.html"
```

Then use <%= props.name %> in your project
```html
<<%= props.name %>></<%= props.name %>>
```

--

### License

MIT © <%= props.author =>

[bower-badge]: https://img.shields.io/bower/v/<%= props.name %>.svg
[bowerlicense-badge]: https://img.shields.io/bower/l/<%= props.name %>.svg
[travis-badge]: https://img.shields.io/travis/<%= props.github %>/<%= props.name %>.svg
[travis-url]: https://travis-ci.org/<%= props.github %>/<%= props.name %>
[bowerdeps-badge]: https://img.shields.io/gemnasium/<%= props.github %>/<%= props.name %>.svg
[bowerdeps-url]: https://gemnasium.com/bower/<%= props.name %>
