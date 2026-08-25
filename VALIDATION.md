# Validation Report

Release: `dessert-cutout-from-image` v1.0.0

## Agent Skills specification

Validation target:

```text
dessert-cutout-from-image/
```

Result: **PASS — 0 errors**

Checked against the current canonical `skills-ref` validation rules documented by the Agent Skills specification:

- `SKILL.md` exists.
- `name` is present, lowercase, valid hyphen-case, <= 64 characters, and matches the parent directory exactly.
- `description` is present and <= 1024 characters.
- `compatibility` is a string and <= 500 characters.
- Frontmatter uses only allowed Agent Skills fields.
- `metadata.version` is stored as a string.

Observed values:

```text
name: dessert-cutout-from-image
directory: dessert-cutout-from-image
description length: 428
compatibility length: 96
metadata.version: 1.0.0
errors: 0
```

Canonical command for re-validation in an environment with `skills-ref` installed:

```bash
skills-ref validate ./dessert-cutout-from-image
```

## OpenAI agents/openai.yaml checks

Result: **PASS**

- `interface.display_name` is present.
- `interface.short_description` is 57 characters (required range: 25–64 by OpenAI's skill-creator generator).
- `interface.default_prompt` explicitly invokes `$dessert-cutout-from-image`.
- String values are quoted.
- No unnecessary icon, brand-color, or MCP dependency fields were added.

## Archive layout

Result: **PASS**

The release ZIP has exactly this top-level skill directory:

```text
dessert-cutout-from-image/
```

This matches the `name` field in `SKILL.md`.
