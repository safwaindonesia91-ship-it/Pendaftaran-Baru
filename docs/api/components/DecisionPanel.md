# DecisionPanel

Controls to set decision status, notes, and BA number with permission checks.

## Signature
`DecisionPanel({ decision, setDecision, canDecide, log })`

## Props
- `decision` (object): Current decision.
- `setDecision` (function): Setter.
- `canDecide` (boolean): Permission to change decision.
- `log` (function): Audit logger.

## Example
```jsx
<DecisionPanel decision={decision} setDecision={setDecision} canDecide={can('panel_decision')} log={log} />
```
