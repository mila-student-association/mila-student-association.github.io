# Mila Student Association Website

## Template

This website is based on Alex Hernandez-Garcia site and derivations (ML4Cryo, Julia Kaltenborn's Website).

## Installation

The following packages/software are needed to build the website:
- bundle
- sass stuff
- ruby
- gem

## Commands for building

Ideally run the following commands in separate terminal tabs. 

The following is a SASS (Syntactically Awesome Stylesheets) command used for converting a .scss file into a .css file while continuously watching for changes. When the source scss file changes it automatically recompiles the target css file.

```
sass --watch _sass/mystyles.scss:assets/css/mystyles.css
```

Build it (needs to be done evertime you change configs, yamls, etc.)
Builds to path/to/_site

```
bundle exec jekyll build --watch
```

Run website (in separate terminal) e.g. http://127.0.0.1:4000

```
bundle exec jekyll serve --incremental
```

## CSS structure

Overwrite css properties here:

assets/css/mystyles.css
