# Setup Kubectl

#### Sample workflow to install a specific version of kubectl binary on the runner.

Acceptable values are latest or any semantic version string like `v1.15.0`. Use this action in workflow to define which version of kubectl will be used.

```yaml
- uses: step-security/setup-kubectl@v4
  with:
     version: '<version>' # default is latest stable
  id: install
```

Refer to the action metadata file for details about all the inputs https://github.com/step-security/setup-kubectl/blob/main/action.yml
