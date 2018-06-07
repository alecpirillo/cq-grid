# cq-grid

A Bootstrap 4 based grid implementing cq-prolyfill (container query polyfill) into the breakpoint logic.

## Usage

With this grid you can use Bootstrap style grid classes in your html in the following form:

```html
<link rel="https://unpkg.com/cq-grid@0.1.2/dist/cq-grid.min.css">
<script src="https://unpkg.com/cq-prolyfill@0.4.0/cq-prolyfill.min.js"></script>
...
<div class="container-fluid">
    <div class="row">
        <div class="cq-col-md-12">...</div>
        <div class="cq-col-md-5 cq-col-sm-8 cq-col-12">...</div>
    </div>
</div>
```

If your using this grid in a page with bootstrap 4 css, please use the addon version instead to avoid conflicts in row/container CSS:

```html
<link rel="https://unpkg.com/cq-grid@0.1.2/dist/cq-grid-addon.min.css">
<script src="https://unpkg.com/cq-prolyfill@0.4.0/cq-prolyfill.min.js"></script>
...
<div class="container-fluid">
    <div class="row">
        <div class="cq-col-md-12">...</div>
        <div class="cq-col-md-5 cq-col-sm-8 cq-col-12">...</div>
    </div>
</div>
```

## Contribute

* Create a [new issue on GitHub](https://github.com/damanptyltd/cq-grid/issues/new) if you have a question, a suggestion or found a bug.
* Spread the word about this project.

## Built With

* [Bootstrap 4 Grid](https://getbootstrap.com/docs/4.1/getting-started/introduction/)
* [cq-prolyfill](https://github.com/ausi/cq-prolyfill/blob/master/docs/index.md)

## Versioning

We use [SemVer](http://semver.org/) for versioning.

## Authors

* **Alec Pirillo** - *Initial work*

## License

MIT