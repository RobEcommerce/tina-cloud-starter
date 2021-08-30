---
blocks:
  - tagline: ''
    headline: Welcome to RobEcommerce
    text: >-
      This is a first pass at Tina, y'all


      `content/pages/home.md`, components from `components/blocks`, and puts
      them all together in `pages/[filename].tsx`, all based on a schema defined
      in `.tina/schema.ts`.
    actions:
      - label: Get Started
        type: button
        icon: true
        link: /posts
      - label: Read Blog
        type: button
        icon: false
        link: /posts
    image:
      src: >-
        https://res.cloudinary.com/forestry-demo/image/upload/v1628102029/tina-cloud-starter/tina-illustration.WebP
      alt: Tina y'all
    color: default
    _template: hero
  - items:
      - icon:
          color: ''
          style: float
          name: ''
        title: Here's Another Feature
        text: >-
          This is where you might talk about the feature, if this wasn't just
          filler text.
      - icon:
          color: red
          style: float
          name: code
        title: Amazing Feature
        text: >-
          Aliquam blandit felis rhoncus, eleifend ipsum in, condimentum nibh.
          Praesent ac faucibus risus, eu lacinia enim.
      - icon:
          color: green
          style: float
          name: palette
        title: Configurable Theme
        text: >-
          Edit global theme configuration with Tina. Change your theme's primary
          color, font, or icon set.
      - icon:
          color: yellow
          style: float
          name: like
        title: This Is a Feature
        text: New Features coming soon
    color: default
    _template: features
---

