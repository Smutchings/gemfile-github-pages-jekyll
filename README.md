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
