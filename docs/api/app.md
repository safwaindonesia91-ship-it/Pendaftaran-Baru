# App (default export)

`App` is the main React function component exported as default within `Assessment_RPL.html`. It orchestrates tabs, role/permissions, local state, optional API sync, audit logging, and the end-to-end flows for RPL Type A and Type B.

## Responsibilities
- Tab navigation (`overview`, `typeA`, `typeB`, `asses`, `docs`, `audit`, `settings`)
- Role-based permissions using `PERMS`
- Local persistence via `useLocalStorage`
- Optional sync to JSON Server endpoints using `apiFetch`
- Data import/export via `UploadButton` and `JsonExportButton`
- Evidence logging and decisions with audit trail

## Public Behavior (User-Facing)
- Users can switch roles, upload validated documents, run assessments, generate BA numbers, and preview SK summaries.

## Important Derived Helpers
- `can(action)`: Check whether current role permits an action.
- `log(action, detail)`: Append an audit entry; POST to `/audit` when API enabled.
- `mkSksRecognized(cpRatings, mk)`: Heuristic to compute recognized SKS for a course.
- `importBundle(json)`: Import a data bundle exported from the app.

## Example Usage
The app is embedded as an inline React component; when bundling separately, render `<App />` inside a React root.
