# gptAction

Helper to POST to arbitrary custom action endpoints under `/actions/*` with metadata.

## Signature
`async function gptAction(path, payload)`

## Params
- `path` (string): Action path, e.g., `/actions/upsert`.
- `payload` (object): Arbitrary payload passed in `payload` field.

## Returns
- Parsed JSON response.

## Errors
- Throws when API disabled or response not OK.

## Example
```js
await gptAction('/actions/upsert', { entity: 'evidence', data: { /* ... */ } });
```
