# Building the doc locally

## First setup

First install `rbenv` and `ruby-build` through the package manager
Then run the following commands in a shell:

```
$ eval "$(rbenv init -)"
$ rbenv install 2.7.3
$ rbenv shell 2.7.3
$ bundle update
```

## Building the cods

```
$ eval "$(rbenv init -)"
$ rbenv shell 2.7.3
$ bundle exec jekyll serve
```

Wait a bit (30 seconds or something like that).
Then the doc will be accessible from a web browser at http://localhost:4000 by default.

# Color scheme
<img src="/assets/color_scheme.png" alt="">
