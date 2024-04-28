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

Where, `<collection-name>` is the name of the collection, and `<directory>` is the directory you want to list the pages in, use slash `/` to separate the directories. For most of page related commands, you can use the `-d` flag to specify the directory you want to operate on, or not to specify the directory to operate on the root directory of the collection.
