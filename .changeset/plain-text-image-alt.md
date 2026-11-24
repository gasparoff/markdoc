---
'@markdoc/markdoc': patch
---

Use the plain text of an image description as its `alt` attribute, so `![foo *bar*](/url)` produces `alt="foo bar"` instead of the raw Markdown source. Descriptions containing variables or tags keep their source text. The formatter now writes the plain-text description, escaping Markdown characters.
