---
layout: default
---

# Render Page with Imbricate CLI

Imbricate CLI provides a way to render a page from your origin. You can use the the following command to render a page:

{% capture render-page %}
imbricate page render -c <collection-name> -i <page-identifier>
{% endcapture %}

{% include copyable/copyable-text-highlight.html
    shell="any-terminal"
    language="shell"
    text=render-page
%}

This will render the page with the given collection name and page identifier. The rendered page will be displayed in the terminal. If you want to save the rendered page to a file, you can use the `-o` flag:

{% capture render-page-save %}
imbricate page render -c <collection-name> -i <page-identifier> -o <output-file>
{% endcapture %}

{% include copyable/copyable-text-highlight.html
    shell="any-terminal"
    language="shell"
    text=render-page-save
%}

## Using a template

You can also render a page using a template. You can use the `-e` flag to specify the template to use:

{% capture render-page-template %}
imbricate page render -c <collection-name> -i <page-identifier> -e <template-name>
{% endcapture %}

{% include copyable/copyable-text-highlight.html
    shell="any-terminal"
    language="shell"
    text=render-page-template
%}

The template could includes some placeholders to let imbricate CLI to replace them with the page content. You could visit the [Template](/template) page to learn more about how to create a template for your page.
