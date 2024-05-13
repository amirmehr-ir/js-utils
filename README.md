# js-utils

```js
function getFileExtension(filename) {
  if (typeof filename !== 'string') return '';
  
  const parts = filename.split('.');
  return parts.length > 1 ? parts.pop() : '';
}
```
