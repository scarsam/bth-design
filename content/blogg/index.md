---
views:
  main:
    template: anax/v2/article/default
    data:
      class: blog

  byline: false
  block-about: false
  article-toc: false

  blog-list:
    region: main
    template: anax/v2/blog-list/default
    sort: 2
    data:
      dateFormat: j F Y
      meta:
        type: toc
        orderby: publishTime
        orderorder: desc

  blog-toc:
    region: sidebar-right
    template: anax/v2/blog-toc/default
    sort: 2
    data:
      meta:
        type: copy
        view: blog-list
---

# Dagens Bild

Här testar laddar jag upp olika bilder och testar olika verktyg, allt från Cimage till LESS-modulen @desinax/figure. Jag kommer att prova att beskära, skala om eller proceessa olika bilder.
