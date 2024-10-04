---
# Homepage
type: widget_page
  {{ $content := readFile "/authors/신하윤/index.md" }}
  {{ markdownify $content }}


# Homepage is headless, other widget pages are not.
headless: true
---
