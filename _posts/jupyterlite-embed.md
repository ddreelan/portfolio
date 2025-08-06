---
title: "JupyterLite Notebook Embed"
layout: single
classes: wide
---

Below is a live embedded JupyterLite notebook running fully in your browser.

<iframe
  src="{{ '/lite/retro/notebooks/hello_jupyterlite.ipynb' | relative_url }}"
  width="100%"
  height="800"
  style="border: 1px solid #ccc;">
</iframe>

---

### How this works

- Uses the Retro notebook interface (lighter than full Lab)  
- Notebook file is loaded directly from `/lite/notebooks/`  
- Runs entirely client-side with no server  
- Great for embedding a single notebook in your site  