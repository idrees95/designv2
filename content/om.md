---
views:
    kursrepo:
        region: sidebar-right
        template: anax/v2/block/default
        data:
            meta:
                type: single
                route: block/om-kursrepo

    redovisa:
        region: sidebar-right
        template: anax/v2/block/default
        data:
            meta:
                type: single
                route: block/om-redovisa
    flash:
        region: flash
        template: anax/v2/image/default
        data:
            src: "image/flashimg.jpg??width=1400&amp;height=200&amp;crop-to-fit"
    byline:
        region: main
        template: anax/v2/block/default
        sort: 2
        data:
            meta:
                type: single
                route: block/byline
---

Om
=========================

Detta innehåll är skrivet i markdown och du hittar innehållet i filen `content/om.md`.

Kursen handlar om design, där vi lägger mycket fokus på hur en hemsida ska se ut, vad
vi kan göra för att själva designet ska inte ta lång tid.

[FIGURE src=image/car.png?w=300 caption="Lambo."]
