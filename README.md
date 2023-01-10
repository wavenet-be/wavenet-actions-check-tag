# Check Tag
Very small action to check if the workflow has been run from a tag and generate an error if not.

## Usage
```yaml
jobs:
  qc:
    runs-on: unbuntu-latest
    name: Quality Control

    steps:
      - name: Check if run from tag
        uses: wavenet-be/wavenet-actions-check-tag@v1
```