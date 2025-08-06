---
title: "Try JupyterLite"
layout: single
classes: wide
header_scripts:
  - https://cdn.jsdelivr.net/npm/@jupyterlite/notebook-embed@0.3.0/dist/style.css
  - https://cdn.jsdelivr.net/npm/@jupyterlite/notebook-embed@0.3.0/dist/index.js
---

{% raw %}
<jupyterlite-wasm
  src="{{ '/assets/notebooks/my_notebook.ipynb' | relative_url }}"
  width="100%"
  height="600px">
</jupyterlite-wasm>
{% endraw %}