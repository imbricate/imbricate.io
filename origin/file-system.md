---
layout: default
---

# Imbricate File System Origin

GitHub: [imbricate/imbricate-origin-file-system](https://github.com/imbricate/imbricate-origin-file-system)

## Supported Sandbox Feature

### `import { createPage } from "origin:page"`

Input:

{% capture create-page-input %}
{
    readonly collection: string;
    readonly title: string;

    readonly content?: string;
}
{% endcapture %}

{% include copyable/copyable-text-highlight.html
    shell="any-terminal"
    language="typescript"
    text=create-page-input
%}

Output:

{% capture create-page-output %}
{
    readonly title: string;
    readonly identifier: string;
}
{% endcapture %}

{% include copyable/copyable-text-highlight.html
    shell="any-terminal"
    language="typescript"
    text=create-page-output
%}

### `import { searchPages } from "origin:page"`

Input:

{% capture search-pages-input %}
{
    readonly collection: string;
    readonly keyword: string;

    readonly exact?: boolean;
}
{% endcapture %}

{% include copyable/copyable-text-highlight.html
    shell="any-terminal"
    language="typescript"
    text=search-pages-input
%}

Output:

{% capture search-pages-output %}
{
    readonly results: ImbricatePageSearchResult[];
}
{% endcapture %}

{% include copyable/copyable-text-highlight.html
    shell="any-terminal"
    language="typescript"
    text=search-pages-output
%}
