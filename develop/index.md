---
layout: default
---

# Develop with Imbricate

Imbricate is a open source project managed under the [Imbricate GitHub Organization](https://github.com/imbricate) / [Package Status](/status).

Imbricate are separated by three layers.

- Frontend Interface
- Imbricate Core
- Backend Origin

The Frontend Interface is the user interface that users interact with. It consumes a or multiple Imbricate origins that build to implements the Imbricate Core TypeScript structure. See example of the [Imbricate CLI](https://github.com/imbricate/imbricate-cli).

The Imbricate Core is the core of the Imbricate framework. It is a TypeScript structure that defines the data structure and the operations that can be performed on the data. See source code of the [Imbricate Core](https://github.com/imbricate/imbricate).

The Backend Origin is the data storage and retrieval layer. It is responsible for storing and retrieving data from a data store. To provide features such as storing, searching, scripting and etc. See example of the [Imbricate File System Origin](https://github.com/imbricate/imbricate-origin-file-system).

## Stack API

The Stack API is an API standard interface that can be used to develop a generic server-side management solution for Imbricate, and reuse the infrastructure Stack API Origin. See [Imbricate Stack API](https://github.com/imbricate/imbricate-stack-api).

As a server side is capable of the API schema of the Stack API, any Imbricate interface could point to the server via [Imbricate Stack API Origin](https://github.com/imbricate/imbricate-origin-stack-api).

To implement the Stack API so that it can be used by the Imbricate stack-api origin, follow the API guide of the [Imbricate Stack API Guide](https://stack-api.imbricate.io)
