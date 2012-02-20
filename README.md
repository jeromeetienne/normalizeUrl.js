normalizeURL.js is a single function to normalize URL.
It works in brower and node.js.

It uses
[parseURI 1.2](http://blog.stevenlevithan.com/archives/parseuri)
to parse the url. Then normalize it and return it. It is that simple.

## Let's get started

To include it in a webpage

```
    <script src="normalizeUrl.js"></script>
```

To include it in node

```
    var normalizeUrl	= require('../normalizeUrl.js');
```

## to use it

Just use the following line. it is that simple

```
    var newUrl= normalizeUrl(url);
```