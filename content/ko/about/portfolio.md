---
# Homepage
type: widget_page

# Homepage is headless, other widget pages are not.
headless: true
---

---
# Use the Intro widget of the Blog template
widget: about.avatar

# This file represents a page section.
headless: true

# Order that this section will appear in.
weight: 10

author: admin
#design:
#  background:
#    color: '#090a0b'
#    text_color_light: true
#    video:
#      path:  # enter filename of a video in /assets/media
#  css_class: fullscreen
---

안녕하세요!  
저는 전북대학교 컴퓨터인공지능학 신하윤입니다.
{style="font-size: 1.2rem; background: #FFB76B; background: linear-gradient(to right, #FFB76B 0%, #FFA73D 30%, #FF7C00 60%, #FF7F04 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent;"}

제 이력서와 포트폴리오입니다. [resumé](/about/) 🐇

---
# A section created with the Portfolio widget.
# This section displays content from `content/project/`.
# See https://docs.hugoblox.com/widget/portfolio/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: ''
subtitle: ''

content:
# Page type to display. E.g. project.
page_type: project

# Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
filter_default: 0

# Filter toolbar (optional).
# Add or remove as many filters (`filter_button` instances) as you like.
# To show all items, set `tag` to "*".
# To filter by a specific tag, set `tag` to an existing tag name.
# To remove the toolbar, delete the entire `filter_button` block.
filter_button:
- name: All
tag: '*'
- name: 1
tag: ML
- name: 2
tag: CV
- name: 3
tag: NLP

design:
columns: '1'
view:
