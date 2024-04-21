---
layout: default
---

# Imbricate CLI Render Template

Imbricate CLI template supports placeholders to let imbricate CLI to replace them with the page content. 

- {{content}}
- {{title}}

For example, you can create a template with the following content:

```html
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
```
