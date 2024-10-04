---
# Homepage
type: widget_page

# Homepage is headless, other widget pages are not.
headless: true
---

---

widget: about.avatar

headless: true

weight: 10

author: 신하윤
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


widget: portfolio

headless: true

weight: 20

title: ''
subtitle: ''

content:

page_type: project

filter_default: 0

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
