# rivm-aks-gitops

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] rivm-aks-gitops`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree rivm-aks-gitops`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init rivm-aks-gitops
kpt live apply rivm-aks-gitops --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
