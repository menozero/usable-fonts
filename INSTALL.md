# Installation

How to install GitHub Pages/Jekyll to build or render this website.

1. Install Ruby and [Bundler](https://bundler.io/)

``` shell
gem install bundler
```

2. Install [GitHub Pages](https://pages.github.com/) ([Jekyll](https://jekyllrb.com/) and some plugins)

``` shell
bundler config set --local path 'vendor/bundle/'
bundler install
```

3. Generate the website

``` shell
bundler exec jekyll build
```

4. Or serve the website locally on [http://localhost:4000/](http://localhost:4000/)

``` shell
bundler exec jekyll serve --watch
```
