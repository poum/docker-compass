# What is Compass ?

[Compass](http://compass-style.org) is an open-source CSS authoring framework 
which uses the Sass stylesheet language to make writing stylesheets powerful 
and easy. 

# How to use this image ?

```
$ docker run --rm -it -v $(pwd):/code poum/compass:1.0.1 compile --sass-dir /code/scss/ --css-dir /code/css/ --output-style compressed --force
```

## Optional Environment Variables

None.

# Thanks

This images are build on top of [alpine:latest](https://hub.docker.com/_/alpine/) one.
