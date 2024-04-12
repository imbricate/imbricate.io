---
layout: default
---

# Quick Start with Imbricate CLI

Install the Imbricate CLI by running:

```bash
npm install -g imbricate
```

## Setup Origin

The Imbricate CLI requires an origin to store data. You can use the [Imbricate File System Origin](https://github.com/imbricate/imbricate-origin-file-system) to get started.

```bash
imbricate origin add file-system <your-origin-name> <your-origin-path>
```

While `<your-origin-name>` is the name of the origin and `<your-origin-path>` is the path to the origin, where the file-system-origin will use to store your documents with markdown and json format.
