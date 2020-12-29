<p align="center">
  <a href="https://github.com/kota999/github-actions-container-sample/actions"><img alt="GitHub Actions status" src="https://github.com/kota999/github-actions-container-sample/workflows/build-test/badge.svg"></a>
</p>

# Uppercase Action

This action converts a text to uppercase.

## Inputs

### `text`

**Required** The text to be converted to uppercase.

## Outputs

### `uppercase-text`

The text converted to uppercase.

## Example Usage

```yaml
uses: kota999/github-actions-container-sample@v1.0.0
with:
  text: Hello, World!
```
