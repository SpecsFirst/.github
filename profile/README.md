# SpecsFirst

SpecsFirst makes spec templates for agent-driven projects easy to share and find.
Its public gallery lists them, and submitting one stays trivial.

## Browse the gallery

**[specsfirst.github.io/gallery](https://specsfirst.github.io/gallery/)**

Filter templates by kind and tag, sort them by votes or by latest update, and
vote or comment on each one. Templates can be hosted on any git forge.

## Share a template

A gallery entry is a five-line YAML file, `templates/<id>.yml`, sent as a pull
request. Here is a real one:

```yaml
name: Multi repo specs template
url: https://gitlab.inria.fr/dev-studio/specs-template
description: A model-agnostic specs repo driving several code repos, with task files as contracts between orchestrator and coder.
kind: software
tags: [multi-repo]
```

The gallery detects everything else itself: license, tool-specific files,
last update and a preview.

- [How to contribute](https://github.com/SpecsFirst/gallery/blob/main/CONTRIBUTING.md)
- [The gallery repository](https://github.com/SpecsFirst/gallery)
