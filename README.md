# VM Lint

A super SIMPLE linter made with love 😘

## Install

Add `vm_lint` as dependency to your `pubspec.yaml`
```yaml
dependencies:
  vm_lint:
    git:
      url: https://github.com/teddichiiwa/vm_lint.git
```

Create a `analysis_options.yaml` file in the root of your project and import the `vm_lint` rules:

```yaml
include: package:vm_lint/analysis_options.yaml
```
