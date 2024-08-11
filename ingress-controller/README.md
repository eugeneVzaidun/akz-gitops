# ingress-controller

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] ingress-controller`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree ingress-controller`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init ingress-controller
kpt live apply ingress-controller --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
