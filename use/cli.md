---
layout: default
---

# Quick Start with Imbricate CLI

Install the Imbricate CLI by running:

{% capture install-imbricate %}
npm install -g imbricate
{% endcapture %}

{% include copyable/copyable-text-highlight.html
    shell="any-terminal"
    language="shell"
    text=install-imbricate
%}

## Setup Origin

The Imbricate CLI requires an origin to store data. You can use the [Imbricate File System Origin](https://github.com/imbricate/imbricate-origin-file-system) to get started.

{% capture install-imbricate %}
imbricate origin add file-system <your-origin-name> <your-origin-path>
{% endcapture %}

{% include copyable/copyable-text-highlight.html
    shell="any-terminal"
    language="shell"
    text=install-imbricate
%}

While `<your-origin-name>` is the name of the origin and `<your-origin-path>` is the path to the origin, where the file-system-origin will use to store your documents with markdown and json format.
