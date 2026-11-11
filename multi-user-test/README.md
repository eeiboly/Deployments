# multi-user-test

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] multi-user-test`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree multi-user-test`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init multi-user-test
kpt live apply multi-user-test --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
