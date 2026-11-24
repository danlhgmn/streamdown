---
"streamdown": minor
---

Add `mermaid.deferRender` with `root`, `rootMargin`, and `isCached`, so inline diagrams in a scroll container start to render before they come into view, and cached diagrams render without the debounce and idle wait.
