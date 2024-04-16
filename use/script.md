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

## Write a Script

You can write your script in the script file that you created. Here is an example of a script that outputs "Hello, World!" to the terminal:

{% capture write-script %}
import { print } from "interface:io";
print("Hello, World!");
{% endcapture %}

{% include copyable/copyable-text-highlight.html
    shell="any-terminal"
    language="javascript"
    text=write-script
%}

## Running a Script

To run a script, you can use the following command:

{% capture run-script %}
imbricate script run -s my-script
{% endcapture %}

{% include copyable/copyable-text-highlight.html
    shell="any-terminal"
    language="shell"
    text=run-script
%}

This will run the script and output the result to the terminal.
