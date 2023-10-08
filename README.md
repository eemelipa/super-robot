# Current Behavior

Renovate bot run gives lookup warnings:

```txt
WARN: Package lookup failures (branch="renovate/typescript-5.x")
{
  "warnings": [
    "Failed to look up npm package @renovatebot/eslint-plugin"
  ]
  "files": [
    "package.json"
  ]
}
```

This might be caused by Github requiring authentication before getting read access to the Github package registry.

# Expected Behavior

Renovate is able to update packages without warnings.
