# nodecg-vaadin-text-field

```sh
bower install StreamsGood/nodecg-vaadin-text-field --save
```

Extends [`vaadin-text-field`](https://vaadin.com/elements/vaadin-text-field/) to add NodeCG replicant support.
* `replicant-name`: The identifier for the replicant.
* `replicant-bundle`: Optional. Defaults to the active bundle.

```html
<nodecg-vaadin-text-field replicant-name="name" replicant-bundle="bundle"></nodecg-vaadin-text-field>
```

For a full list of supported attributes, see the [`vaadin-text-field`](https://vaadin.com/elements/vaadin-text-field/) documentation.

---

**Note:** This does not specify styling for vaadin-elements, you will need to install and include either the `vaadin-material-theme` or `vaadin-valo-theme` yourself.

```sh
bower install vaadin/vaadin-material-theme --save
```

```html
<link rel="import" href="bower_components/vaadin-material-theme/vaadin-text-field.html">
```