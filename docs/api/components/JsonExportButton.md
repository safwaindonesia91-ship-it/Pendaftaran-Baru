# JsonExportButton

Button to export given data as a downloadable JSON file.

## Signature
`JsonExportButton({ data, filename = 'rpl-data.json', disabled })`

## Props
- `data` (object): Data to serialize.
- `filename` (string): Target filename.
- `disabled` (boolean): Disable the button.

## Example
```jsx
<JsonExportButton data={dataBundle} filename="backup.json" />
```
