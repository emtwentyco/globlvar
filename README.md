# globlvar

This repository stores centrally managed variable groups in YAML files at the repository root:

- `globalvariables.yaml`
- `template-purchase.yaml`
- `template-platform.yaml`

A GitHub Actions workflow loads these groups using `indluni/actions-variable-groups@main` and prints sample values.