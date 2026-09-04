# Trails Updates

This public repository contains metadata used to show Trails product update notices and in-app alerts.

## Browser extension versions

The Trails browser extension reads `extension-versions.json`. Update a store's version only after the corresponding release is available in that store. Chrome and Edge versions may be updated independently.

```json
{
  "chrome": {
    "version": "0.0.44"
  },
  "edge": {
    "version": "0.0.44"
  }
}
```

The extension displays its update message only when the appropriate published version is higher than its installed manifest version.

Additional metadata for the Trails web app can be added alongside `extension-versions.json` as its in-app alert system is introduced.
