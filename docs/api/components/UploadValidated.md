# UploadValidated

Validated document uploader with MIME checks per document type; lists uploaded docs in a table.

## Signature
`UploadValidated({ items, setItems, canUpload })`

## Props
- `items` (Array): Current document records.
- `setItems` (function): Setter for documents.
- `canUpload` (boolean): Permission flag.

## Example
```jsx
<UploadValidated items={docs} setItems={setDocs} canUpload={can('upload_doc')} />
```
