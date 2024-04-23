---
layout: default
---

# Imbricate CLI Render Template

Imbricate CLI template supports placeholders to let imbricate CLI to replace them with the page content. 

{% raw %}
- `{{content}}`
- `{{title}}`
{% endraw %}

For example, you can create a template with the following content:

{% capture example-template-1 %}
{% raw %}
<!DOCTYPE html>
<html>
<head>
    <title>{{title}}</title>
</head>
<body>
    <h1>{{title}}</h1>
    <div>{{content}}</div>
</body>
</html>
{% endraw %}
{% endcapture %}

{% include copyable/copyable-text-highlight.html
    language="html"
    text=example-template-1
%}
