# globlvar

This repository stores centrally managed variable groups in YAML files at the repository root:

- `/home/runner/work/globlvar/globlvar/globalvariables.yaml`
- `/home/runner/work/globlvar/globlvar/template-purchase.yaml`
- `/home/runner/work/globlvar/globlvar/template-platform.yaml`

A GitHub Actions workflow loads these groups using `indluni/actions-variable-groups@main` and prints sample values.