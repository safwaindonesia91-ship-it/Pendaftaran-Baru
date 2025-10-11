# API Documentation

This repository contains a small RPL Compliance demo app and a marketing site. This documentation catalogs all public, user-facing APIs (endpoints), functions, and UI components exposed in the app UI code embedded in `Assessment_RPL.html`.

- App: `App` (default export)
- Components: `Section`, `Badge`, `Pill`, `Table`, `JsonExportButton`, `UploadButton`, `RoleBar`, `UploadValidated`, `BATemplate`, `EvidenceEditor`, `DecisionPanel`, `SKPreview`
- Hooks/Utilities: `useLocalStorage`, `apiFetch`, `gptAction`, `accepts`, `autoBANumber`, `downloadText`
- Domain constants: `PRINSIP`, `DEFAULT_CP`, `DEFAULT_MK`, `ROLES`, `PERMS`, `DOC_TYPES`
- Derived helpers inside `App`: `mkSksRecognized`, `importBundle`, `can`, `log`
- Endpoints (JSON Server style): `/applicants`, `/evidence`, `/decisions`, `/audit`, `/settings`, `/actions/upsert`

## Navigation

- Components: `./components/`
- Hooks & Utils: `./hooks/` and `./utils/`
- Constants: `./constants/`
- Endpoints: `./endpoints/`
- App guide: `./app.md`
