# RoleBar

Role selector and API toggle/input bar.

## Signature
`RoleBar({ role, setRole, apiEnabled, setApiEnabled, apiBase, setApiBase })`

## Props
- `role` (string): Current role id.
- `setRole` (function): Setter.
- `apiEnabled` (boolean): Whether API sync is enabled.
- `setApiEnabled` (function): Setter.
- `apiBase` (string): Base URL for JSON Server.
- `setApiBase` (function): Setter.

## Example
```jsx
<RoleBar role={role} setRole={setRole} apiEnabled={apiEnabled} setApiEnabled={setApiEnabled} apiBase={apiBase} setApiBase={setApiBase} />
```
