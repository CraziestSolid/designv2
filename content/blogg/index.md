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
Dagens bild
===========================

En blogg med temat “Dagens bild” som visar upp mina färdigheter i Cimage, shortcode FIGURE och LESS-modulen desinax/figure som stylar figure-element. Jag har valt att presentera bilder på Bob Dylan som är en av de mest inflytelserika artisterna i mitt liv.
