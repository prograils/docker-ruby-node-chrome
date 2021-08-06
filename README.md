# prograils/ruby-node-chrome:latest

Starting point for running Rails specs - includes lastest stable ruby, latest
stable Google Chrome and node 12.x

## What's inside

The supplied `Dockerfile` will create an images for docker containers
with ruby, nodejs and chrome browser

## Getting started

### Getting the image

```
$ docker pull prograils/ruby-node-chrome
```

### Running

```
$ docker run -t -i prograils/ruby-node-chrome
```

### Testing
```
$ bundle exec rspec
```


## References

* [Test Drive Your Dockerfiles with RSpec and ServerSpec](https://robots.thoughtbot.com/tdd-your-dockerfiles-with-rspec-and-serverspec)
