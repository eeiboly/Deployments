# golden-parameters

## Description
Golden Parameters for Day 1 configuration

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] golden-parameters`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree golden-parameters`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init golden-parameters
kpt live apply golden-parameters --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
