# accepts

Checks whether a MIME type matches any entry in an accept list.

## Signature
`function accepts(mime, acceptList)`

## Params
- `mime` (string): MIME type of the file.
- `acceptList` (Array<string>): Accept patterns; entries ending with `/` match by prefix (e.g., `image/`).

## Returns
- `boolean` indicating acceptance.

## Example
```js
accepts('image/png', ['image/', 'application/pdf']); // true
```
