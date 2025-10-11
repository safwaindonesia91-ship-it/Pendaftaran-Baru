# Pill

Selectable rounded button used for tabs/filters.

## Signature
`Pill({ active, onClick, children })`

## Props
- `active` (boolean): Visual active state.
- `onClick` (function): Click handler.
- `children` (ReactNode): Label.

## Example
```jsx
<Pill active={tab === 'overview'} onClick={() => setTab('overview')}>Overview</Pill>
```
