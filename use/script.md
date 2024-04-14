---
layout: default
---

# Scripting with Imbricate

Imbricate support scripting with JavaScript or TypeScript. You can write scripts to automate the process of creating and updating your documentation.

The Imbricate Scripting feature is powered by [Marked](https://marked.sudo.dog/), a secure runtime for JavaScript and TypeScript that runs in a JavaScript sandboxed environment.

## Getting Started

Taking example with Imbricate CLI as the interface, you can run the following command to create a new script file:

{% capture create-script %}
imbricate script create my-script
{% endcapture %}

{% include copyable/copyable-text-highlight.html
    shell="any-terminal"
    language="shell"
    text=create-script
%}

This will create a new script file and open it with your default configuration.
