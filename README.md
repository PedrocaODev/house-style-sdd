# Witness Schema

Installed global OpenSpec `Witness` schema bundle (version 3).

Includes `schema.yaml` and templates (`proposal`, `design`, `spec`,
`tasks`, `plan`, `verify`, `retrospective`).

Artifact DAG: `proposal → design → specs → tasks → plan → verify`,
with `retrospective` requiring both `plan` and `verify` — the schema
blocks archive closeout until the verification record exists.
`apply` requires `plan` and tracks progress in `tasks.md`.

Meant to be installed under `~/.local/share/openspec/schemas/witness`.

Companion global OpenCode commands and skills live in the separate
[`config-opencode`](~/.config/opencode) repo.
