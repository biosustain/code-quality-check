# code-quality-check

Biosustain's best practices check implementation for github actions.

## Usage

```yaml
name: Code quality
description: Workflow to check if project meets the code quality standards of the Biosustain group

on:
  push:
    branches: main
  pull_request:

jobs:
  code-quality-check:
    name: Code quality check
    uses: biosustain/code-quality-check/.github/workflows/code-quality-check.yml@latest
```
