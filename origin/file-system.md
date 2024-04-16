---
layout: default
---

# Imbricate File System Origin

GitHub: [imbricate/imbricate-origin-file-system](https://github.com/imbricate/imbricate-origin-file-system)

## Supported Sandbox Feature

### `import { createPage } from "origin:page"`

Input:

```typescript
{
    readonly collection: string;
    readonly title: string;

    readonly content?: string;
}
```

Output:

```typescript
{
    readonly title: string;
    readonly identifier: string;
}
```

### `import { searchPages} from "origin:page"`

Input:

```typescript
{
    readonly collection: string;
    readonly keyword: string;

    readonly exact?: boolean;
}
```

Output:

```typescript
{
    readonly results: ImbricatePageSearchResult[];
}
```
