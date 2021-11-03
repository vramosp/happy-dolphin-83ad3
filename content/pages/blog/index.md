---
title: Blog
layout: PageLayout
sections:
  - elementId: ''
    colors: colors-b
    backgroundWidth: full
    quote: |
      # Experience it for yourself
    backgroundImage:
      url: /images/BG.png
      altText: Product Marketing Manager Quote
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-36
          - pb-12
        alignItems: flex-start
        justifyContent: center
      quote:
        textAlign: left
      name:
        fontWeight: 400
        fontStyle: normal
        textAlign: left
      title:
        fontWeight: 400
        fontStyle: normal
        textAlign: left
    type: QuoteSection
  - type: FeaturedPostsSection
    variant: variant-a
    colors: colors-a
    backgroundWidth: full
    title: Current offers
    posts:
      - content/pages/blog/post-three.md
      - content/pages/blog/post-two.md
      - content/pages/blog/post-one.md
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-12
          - pb-12
        alignItems: center
        justifyContent: center
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: center
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: center
      actions:
        justifyContent: center
  - elementId: ''
    colors: colors-a
    backgroundWidth: full
    title: Testimonials
    subtitle: What our customers say about us
    testimonials:
      - quote: >-
          It’s great to see someone taking action while still maintaining a
          sustainable fish supply to home cooks.
        name: Isabelle Parks
        title: Head chef at The Cook
        image:
          type: ImageBlock
          url: /images/isabelle-parks.jpg
          altText: Photo of Isabelle Parks
        styles:
          self:
            margin:
              - mt-0
              - mb-0
            flexDirection: col
          quote:
            textAlign: center
          name:
            fontWeight: 400
            fontStyle: normal
            textAlign: center
          title:
            fontWeight: 400
            fontStyle: normal
            textAlign: center
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-12
          - pb-12
        alignItems: center
        justifyContent: center
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: center
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: center
    type: TestimonialsSection
---
