# Section

A container with title and optional right-aligned element.

## Signature
`Section({ title, children, right })`

## Props
- `title` (string): Title text.
- `children` (ReactNode): Content.
- `right` (ReactNode): Right-side content in header.

## Example
```jsx
<Section title="Struktur CP & Peta MK" right={<Badge>Info</Badge>}>
  <div>...</div>
</Section>
```
