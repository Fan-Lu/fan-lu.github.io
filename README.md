A Github Pages for academic websites. This was forked (then detached) by [Stuart Geiger](https://github.com/staeiou) from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/), which is © 2016 Michael Rose and released under the MIT License. See LICENSE.md.

### Note: if you are using this repo and now get a notification about a security vulnerability, delete the Gemfile.lock file. 

# Instructions

See more info at https://academicpages.github.io/

## To run locally (not on GitHub Pages, to serve on your own computer)

1. Clone the repository and made updates as detailed above 
2. Make sure you have ruby-dev, bundler, and nodejs installed: `sudo apt install ruby-dev ruby-bundler nodejs`
3. Run `bundle clean` to clean up the directory (no need to run `--force`)
4. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again. 
5. Run `bundle exec jekyll liveserve` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.

# Changelog -- bugfixes and enhancements
1. In _data, talks, teaching, guide are commented out as well as these in _pages/cv.md. These sections are currently under develop
2. In _pages, change about.md for introduction
3. In _pages,