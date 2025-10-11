# UploadButton

File input label that reads a JSON file and passes parsed result to `onLoad`.

## Signature
`UploadButton({ onLoad })`

## Props
- `onLoad` (function): Callback receiving parsed JSON.

## Example
```jsx
<UploadButton onLoad={(json) => importBundle(json)} />
```
