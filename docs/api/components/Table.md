# Table

Simple table with column definitions and rows; supports custom render function per column.

## Signature
`Table({ columns, rows, empty })`

## Props
- `columns` (Array<{ key, header, render? }>): Column definitions.
- `rows` (Array<object>): Row data.
- `empty` (string): Message when `rows` is empty.

## Example
```jsx
<Table
  columns={[{ key: 'name', header: 'Nama' }, { key: 'sks', header: 'SKS' }]}
  rows={[{ name: 'MK101', sks: 3 }]}
  empty="Tidak ada data"
/>
```
