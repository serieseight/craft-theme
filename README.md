# Craft theme

A bare bones Craft theme

## Prerequisites

You should copy this theme into the templates directory of
your Craft project.

You should have the latest node and yarn installed.

For development you'll want to navigate to the theme directory.

```
cd path/to/project/craft/templates
```

## Install dependencies

```
yarn install
```

## Run build process

```
yarn build
```

Build and watch for changes:

```
yarn watch
```

## Editing

Source CSS, Javascript and images live inside the `/src` directory.
Gulp compiles these into `/css` `/js` and `/img` directories for
consumption by the UI.
