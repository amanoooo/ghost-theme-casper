# Casper

The default theme for [Ghost](http://github.com/tryghost/ghost/). This is the latest development version of Casper. If you're just looking to download the latest release, head over to the [releases](https://github.com/TryGhost/Casper/releases) page.

# Development

Casper styles are compiled using Gulp/PostCSS to polyfill future CSS spec. You'll need Node and Gulp installed globally. After that, from the theme's root directory:

```bash
$ yarn install
$ yarn dev
```

Now you can edit `/assets/css/` files, which will be compiled to `/assets/built/` automatically.

The `zip` Gulp task packages the theme files into `dist/<theme-name>.zip`, which you can then upload to your site.

```bash
$ yarn zip
```
# Demo

[SITE](http://fe2o3.club:8000)

# Upgrade logs

1.  [add comment](https://github.com/amanoooooooooooooooo/ghost-theme-casper/commit/8fe80c34bbfcb65a57cd328ead1ee3039cb9b793)

2.  [add toc](https://github.com/amanoooooooooooooooo/ghost-theme-casper/commit/1ec342ee18324456f8d0842695cb158a649d4444)
