# autoBANumber

Generates a sequential BA number with prefix and year.month, stored in localStorage counter `rpl.ba.seq`.

## Signature
`function autoBANumber(prefix = 'BA/RPL')`

## Returns
- `string` BA number like `BA/RPL/2025.10/0001`.

## Example
```js
const no = autoBANumber();
```
