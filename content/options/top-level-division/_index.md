---
format: [html4, html5, html+lhs, html5+lhs, s5, slidy, slideous, dzslides, revealjs]
value: [default, section, chapter, part]
---

Treat top-level headings as the given division type in LaTeX, ConTeXt, DocBook, and TEI output. The hierarchy order is part, chapter, then section; all headings are shifted such that the top-level heading becomes the specified type. The default behavior is to determine the best division type via heuristics: unless other conditions apply, section is chosen. When the documentclass variable is set to report, book, or memoir (unless the article option is specified), chapter is implied as the setting for this option. If beamer is the output format, specifying either chapter or part will cause top-level headings to become \part{..}, while second-level headings remain as their default type.


