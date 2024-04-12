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
imbricate origin add file-system <ORIGIN-NAME> <ORIGIN-PATH>
{% endcapture %}

{% include copyable/copyable-text-highlight.html
    shell="any-terminal"
    language="shell"
    text=install-imbricate
%}

While `<ORIGIN-NAME>` is the name of the origin and `<ORIGIN-PATH>` is the path to the origin, where the file-system-origin will use to store your documents with markdown and json format.
