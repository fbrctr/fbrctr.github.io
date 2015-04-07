<p align="center">
  <img src="http://fbrctr.github.io/assets/toolkit/images/logo.svg" width="500">
</p>

This is the [Fabricator](https://github.com/fbrctr/fabricator) instance used to build [http://fbrctr.github.io](http://fbrctr.github.io).

## Development

Checkout the `fabricator` branch:

```
$ git checkout fabricator
```

Start local dev server:

```
$ npm start
```

Build for release:

```
$ npm run build
```

Publish:

```
$ git subtree push --prefix dist origin master
```
