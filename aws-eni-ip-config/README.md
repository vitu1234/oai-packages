# aws-eni-ip-config

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] aws-eni-ip-config`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree aws-eni-ip-config`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init aws-eni-ip-config
kpt live apply aws-eni-ip-config --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
