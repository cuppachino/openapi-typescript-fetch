# @cuppachino/openapi-fetch

## 2.2.0

### Minor Changes

- 456668e: fix issue 22 - allow sending FormData as body

## 2.1.2

### Patch Changes

- 2dfe398: fix type export path

## 2.1.1

### Patch Changes

- b1b5b74: pass type errors

## 2.1.0

### Minor Changes

- 7aec33f: created fetches that previously required a `Record<string, never>` (empty object) as its first argument now allow that argument to be undefined.

### Patch Changes

- ce0f69a: make `Record<string, never>` payloads optional

## 2.0.6

### Patch Changes

- a892a68: fix: set default entry point to cjs output. Only affects targets that ignore the exports field in package.json.
- 68657ec: retry ci action

## 2.0.5

### Patch Changes

- 0194f01: fix: coerce undefined body to null (stricter dev types)

## 2.0.4

### Patch Changes

- c8b204a: Use exact optional query parameters

## 2.0.3

### Patch Changes

- e6cac56: Update package.json

## 2.0.2

### Patch Changes

- 97048c2: deps: add remark

## 2.0.1

### Patch Changes

- f0cab17: change package name
