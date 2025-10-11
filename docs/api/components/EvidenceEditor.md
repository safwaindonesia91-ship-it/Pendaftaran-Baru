# EvidenceEditor

Editor to add evidence records and display them in a table. Triggers audit via `log`.

## Signature
`EvidenceEditor({ items, setItems, log, canEdit })`

## Props
- `items` (Array): Evidence list.
- `setItems` (function): Setter.
- `log` (function): Audit logger.
- `canEdit` (boolean): Permission flag.

## Example
```jsx
<EvidenceEditor items={evidence} setItems={setEvidence} log={log} canEdit={can('record_evidence')} />
```
