# useLocalStorage

Persisted state hook with JSON serialization and graceful error handling.

## Signature
`const [state, setState] = useLocalStorage(key, initial)`

## Params
- `key` (string): LocalStorage key.
- `initial` (any): Initial value when nothing stored or parsing fails.

## Behavior
- Initializes from `localStorage[key]` if present and parses JSON safely.
- Writes to `localStorage` whenever state changes.

## Example
```jsx
const [applicant, setApplicant] = useLocalStorage('rpl.applicant', { name: '', id: '' });
```
