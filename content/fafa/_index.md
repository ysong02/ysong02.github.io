---
title: "Fafa"
type: landing
# (optional) add to navbar
menu:
  main:
    name: Fafa
    weight: 40
sections:
  - block: collection
    content:
      title: Fafa

      reading_time: false
      filters:
        folders: ["fafa"]   # ← this section itself (content/fafa/)
      count: 100
      sort: date_desc
    design:
      view: masonry         # other options: cards, showcase, compact
      columns: 3
---
