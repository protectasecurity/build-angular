# Build Angular GitHub Actions

Build Angular GitHub Actions allows you to build Angular projects

## Example usage

```yaml
on: [push]

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: protectasecurity/build-angular@v1
```
Output Artifact: dist


## Inputs

- `node-version` **Optional** Node JS version to use
- `workspace` **Optional** Relative path under $GITHUB_WORKSPACE to place the project

## Authors

- [Ronnie Ayala](https://github.com/ronnieacs)