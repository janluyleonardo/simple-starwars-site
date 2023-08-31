# Simple Star Wars Site

This is a raw, static HTML site packed with information about Star Wars
movies, taken from the [Wookieepedia][1].

## Serving the site locally

Although this site can be viewed by simply opening the `.html` files, you would
get a better user experience by serving it using Python's `SimpleHTTPServer` or
`http.server` modules.

To serve this site locally, execute the following commands in a terminal window:

> For this to work, you will have to install [Python][2] on your machine.

```
$ cd simple-starwars-site
$ python -m SimpleHTTPServer 8080  # If you have Python 2.7 installed
$ python -m http.server 8080       # If you have Python 3 installed
```

After this, you can fire up your favorite web browser and put
[http://localhost:8080][3] in the address bar.

[1]: http://starwars.wikia.com/wiki/Main_Page
[2]: https://www.python.org/downloads/
[3]: http://localhost:8080
