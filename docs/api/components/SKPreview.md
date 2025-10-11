# SKPreview

Preview component for SK summary depending on RPL type (A or B).

## Signature
`SKPreview({ tipe, applicant, recognized, totalSks, kkniLevel, decision })`

## Props
- `tipe` ("A" | "B"): RPL type.
- `applicant` (object): Applicant info.
- `recognized` (Array): Recognized MK list (for type A).
- `totalSks` (number): Total recognized SKS (for type A).
- `kkniLevel` (string|number): Target KKNI level (for type B).
- `decision` (object): Decision object.

## Example
```jsx
<SKPreview tipe="A" applicant={applicant} recognized={recognized} totalSks={totalSks} />
```
