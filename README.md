## Website

Comparative modENCODE/ENCODE project website built with [Jekyll](jekyllrb.com), [SASS](http://www.sass-lang.com), [Bourbon](http://bourbon.io), [Neat](http://neat.bourbon.io), and [Bitters](http://bitters.bourbon.io).

### Set Up Environment

```ShellSession
$ gem install jekyll
```

The site works with Jekyll 2.0.0 or later.

### Build Site

To build the static HTML and CSS for deployment use the Jekyll ```build``` command. A range of deployment strategies is discussed in the [Jekyll documentation](http://jekyllrb.com/docs/deployment-methods/). 

```ShellSession
$ jekyll build
```

To build the site for production deployment outside GitHub pages, the default ```baseurl``` in ```_config.yml``` needs to be overwritten using the ```baseurl``` defined in ```_config_production.yml```. __Please do not edit the ```baseurl``` in ```_config.yml```.

```
jekyll build --config _config.yml,_config_production.yml
```

### Serve Site

To serve the site locally for development use the Jekyll ```serve``` command.

```ShellSession
$ jekyll serve --baseurl "" --watch
```

### View Site

```ShellSession
$ open http://0.0.0.0:4000/
```

### Optional Setup Instructions

To update the dependencies on Bourbon, Neat or Bitters additional gems are required.

```ShellSession
$ gem install bourbon
$ gem install neat
$ gem install bitters
```

Depending on your system your might have to run those as superuser using ```sudo```.
