# ix-apod web component
Webcomponent that can be used to show the Astronomy Picture of the Day

Nasa publishes a APOD every day (of course :-)): http://apod.nasa.gov/apod/
The ix-apod element uses the ix-apod-data element.
The last one uses NASA's apod API to retrieve the apod data:
https://api.nasa.gov/api.html#apod
For now only the url in the response object is used.

With the apod webcomponent it is possible to have an apod image on your website:

```html
<html>
...
<body>

...

<ix-apod></ix-apod>

...

</body>
</html>
```
