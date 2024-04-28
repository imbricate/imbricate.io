---
layout: default
---

# Imbricate CLI Directory

Imbricate pages are stored in collections. However, although they are not stored in a traditional directory structure, you can still manage them with a directory-like structure using the Imbricate CLI.

{% capture list-page-in-directory %}
imbricate page list -c <collection-name> -d <directory>
{% endcapture %}

{% include copyable/copyable-text-highlight.html
    shell="any-terminal"
    language="shell"
    text=list-page-in-directory
%}
