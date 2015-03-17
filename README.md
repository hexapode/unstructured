# Unstructured
An unstructured, schema less Database


-

##Usage

First install the npm package

```
	npm install unstructured
```

## Example
```
var unstructured = require('unstructured');

unstructured.save({test: 'Lol'});
unstructured.save('This is a fullText example');
unstructured.save('<test></test>');
unstructured.save(Image);
unstructured.list().then(
	function(data) {
		console.log(data);
	}
)

```