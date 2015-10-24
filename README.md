# ix-apod web component
Webcomponent that can be used to retrieve the Astronomy Picture of the Day data

Nasa publishes a APOD every day (of course :-)): http://apod.nasa.gov/apod/

ix-apod-data uses NASA's APOD API to retrieve the apod data:
https://api.nasa.gov/api.html#apod

With the apod webcomponent it is possible to use APOD data on your website:

```html
<html>
...
<body>

...

<ix-apod-data apod="{{data}}"></ix-apod-data>

...

</body>
</html>
```
