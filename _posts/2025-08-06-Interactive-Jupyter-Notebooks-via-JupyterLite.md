---
title: "JupyterLite Demo"
permalink: /jupyterlite-demo/
layout: single
classes: wide
header_scripts:
  - https://cdn.jsdelivr.net/npm/@jupyterlite/notebook-embed@0.3.0/dist/style.css
  - https://cdn.jsdelivr.net/npm/@jupyterlite/notebook-embed@0.3.0/dist/index.js
---

Below is a **live, runnable** Jupyter notebook powered by [JupyterLite](https://jupyterlite.readthedocs.io).  
It runs **entirely in your browser** — no server, no Python install required.

{% raw %}
<jupyterlite-wasm
  src="{{ '/assets/notebooks/GmailToCalendar.ipynb' | relative_url }}"
  width="100%"
  height="600px">
</jupyterlite-wasm>
{% endraw %}

---

### How it Works
- **`<jupyterlite-wasm>`** is a custom web component provided by the JupyterLite team.
- Your `.ipynb` is fetched from `/assets/notebooks/`.
- All execution happens **client‑side** using [Pyodide](https://pyodide.org/).

💡 *Tip:* You can change the `height="600px"` to make it taller.