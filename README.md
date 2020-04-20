# gemfile-github-pages-jekyll
A Gemfile containing the latest Github Pages dependencies. A handy tool when running Github Pages locally for testing.

## How to use
To use this Gemfile, just download it into the `/src` directory of your GitHub Pages project. Then you can use your favourite Gem manager to install the gems.

## Which version of GitHub Pages is this for?
The supported version of GitHub Pages will always be marked in the latest commit.

The initial version of this Gemfile is for Jekyll 3.8.5 and GitHub Pages 204.

## Where do these values come from?

These values come from the [Dependency Versions | GitHub Pages](https://pages.github.com/versions/) documentation.

## What if I get errors showing a newer Gem version than is shown in this list?
You'll need to use `gem uninstall [gem-name]` to uninstall versions that are newer than those listed here, as they can cause issues with Jekyll loading.

# Installing GitHub Pages for local development

| Install on macOS  | Install on Windows |
| ----------------- | ------------------ |
| 1) Install Homebrew      | 1) Install RubyInstall for Windows        |
| 2) Use Homebrew to install rbenv or RVM     | 2) Use RubyInstaller to install Ruby 2.5.3       |
| 3) Use rbenv or RBM to install Ruby 2.5.3  | 3) Install Ruby Bundler |
| 4) Set your Ruby version to 2.5.3| 4) Set your Ruby version to 2.5.3 | 
| 5) Install Bundler | 5) Install "tzinfo-data" Gem |
| 6) Run `cd [blog-name]` to create folder for Jekyll | 
| 7) Download this repo's GEMFILE to the Jekyll directory |
| 8) Run `bundler update` to install required Gems |
| 9) Run ` bundle exec jekyll new` to create the new JEkyll blog |
| 10) Run `bundle exec jekyll s -w --host 0.0.0.0` to serve an auto-regenerating version of your Jekyll blog to 0.0.0.0 on your own machine, or your machines' IP address on any machine on your network. |
