---
layout: default
---

# Develop with Imbricate

Imbricate are separated by three layers.

- Frontend Interface
- Imbricate Core
- Backend Origin

The Frontend Interface is the user interface that users interact with. It consumes a or multiple Imbricate origins that build to implements the Imbricate Core TypeScript structure. See example of the [Imbricate CLI](https://github.com/imbricate/imbricate-cli).

The Imbricate Core is the core of the Imbricate framework. It is a TypeScript structure that defines the data structure and the operations that can be performed on the data. See source code of the [Imbricate Core](https://github.com/imbricate/imbricate).

The Backend Origin is the data storage and retrieval layer. It is responsible for storing and retrieving data from a data store. To provide features such as storing, searching, scripting and etc. See example of the [Imbricate File System Origin](https://github.com/imbricate/imbricate-origin-file-system).
