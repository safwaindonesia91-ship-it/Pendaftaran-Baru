# BATemplate

Form to manage and generate BA (Berita Acara) number and text; supports download.

## Signature
`BATemplate({ decision, applicant, panel, onGenerate })`

## Props
- `decision` (object): Decision state.
- `applicant` (object): Applicant info.
- `panel` (Array<string>): Panel member names.
- `onGenerate` (function): Callback when BA data changes.

## Example
```jsx
<BATemplate decision={decision} applicant={applicant} panel={["Asesor", "Senat", "SPMI"]} onGenerate={setDecision} />
```
