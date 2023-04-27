# Regex-helpers

### Remove non-alphahumeric characters from a string: 

```js
string.replace(/[^A-Za-z0-9]/g, '');

```
### The following regex removes non-alphanumeric chars from an input string:

```js
input.replace(/\W/g, '')
```
### \W is the equivalent of [^0-9a-zA-Z_].  However, it does inlcude the underscore character. To also remove underscores use:

```js
input.replace(/[^0-9a-z]/gi, '')
```
