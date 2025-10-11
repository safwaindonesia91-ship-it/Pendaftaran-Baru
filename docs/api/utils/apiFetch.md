# apiFetch

Fetch helper targeting a JSON Server-style API. Throws when API base URL is not set or response is not OK.

## Signature
`async function apiFetch(path, opts = {})`

## Params
- `path` (string): Endpoint path, e.g., `/audit`.
- `opts` (object): Fetch options; automatically includes `Content-Type: application/json`.

## Returns
- Parsed JSON response.

## Errors
- Throws `Error("API disabled")` when base URL is empty.
- Throws `Error("API <status>")` on non-2xx responses.

## Example
```js
await apiFetch('/audit', { method: 'POST', body: JSON.stringify(entry) });
```
