---
_schema: default
title: All Components
pageSections:
  - _component: page-sections/heroes/hero-card
    id: heroCard
    eyebrowIcon:
    heading: Card Hero Section Title
    subtext:
    card:
      usePost: true
      post: >-
        /src/content/blog/five-signs-your-cdn-is-lying-to-you-about-cache-hit-rates.mdx
      eyebrowText: Card Hero Eyebrow
      heading: Card Hero Heading
      subtext: Card Hero Subtext
      buttonSections: []
      counters:
        - counter:
            number: 100
            prefix: $
            suffix: M
          subtext: Counter Subtext
        - counter:
            number: 999
            prefix: $
            suffix: M
          subtext: Counter Subtext
    maxContentWidth: 2xl
    paddingVertical: 4xl
    colorScheme: light
    backgroundColor: base
    verticalOffset: {}
    rounded: true
  - _component: page-sections/heroes/hero-center
    id: hero-center
    eyebrowIcon: {}
    eyebrowText: Eyebrow placeholder
    heading: Hero Center Test
    headingSize: 4xl
    subtext: Subtext placeholder Hero text
    buttonSections:
      - _component: building-blocks/core-elements/button
        text: Click Now!
        hideText: false
        link: https://www.accuedits.com
        iconName: academic-cap
        iconPosition: before
        variant: primary
        size: md
    image:
      source: ''
      alt: ''
      rounded: true
    icons:
      - name: globe-asia-australia
        color: brand-gradient
        background: true
        size: 4xl
      - name: rocket-launch
        color: brand-gradient
        background: true
        size: 4xl
    backgroundDecoration: true
    sectionHeight: full
    maxContentWidth: xl
    colorScheme: inherit
    backgroundColor: base
    contentBackground: false
    verticalOffset: {}
    rounded: false
description: This page show all components
---
