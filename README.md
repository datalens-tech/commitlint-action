# commitlint-action

[![CI](https://github.com/datalens-tech/commitlint-action/workflows/Check%20PR/badge.svg)](https://github.com/datalens-tech/commitlint-action/actions?query=workflow%3A%22%22Check+PR%22%22)
[![GitHub Marketplace](https://img.shields.io/badge/Marketplace-Template-blue.svg)](https://github.com/marketplace/actions/template)

Action for validate PR tilte for more more semantic meaning to your git history

## Usage

### Example

```yaml
jobs:
  template:
    permissions:
      contents: read

    steps:
      - name: Template
        id: template
        uses: datalens-tech/commitlint-action@v1
```

### Action Inputs

| Name          | Description  | Default |
| ------------- | ------------ | ------- |
| `placeholder` | Placeholder. |         |

### Action Outputs

| Name          | Description  |
| ------------- | ------------ |
| `placeholder` | Placeholder. |

## Development

### Global dependencies

- [Taskfile](https://taskfile.dev/installation/)
- [nvm](https://github.com/nvm-sh/nvm?tab=readme-ov-file#install--update-script)

### Taskfile commands

For all commands see [Taskfile](Taskfile.yaml) or `task --list-all`.

## License

[MIT](LICENSE)
