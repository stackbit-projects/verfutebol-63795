---
title: Home
sections:
  - type: blog_feed_section
    title: jogos de hoje
    blog_feed_cols: three
    enable_cards: true
    show_recent: true
    recent_count: 6
    show_image: true
    show_date: true
    show_categories: false
    show_author: false
    show_excerpt: false
    align: center
    padding_top: medium
    padding_bottom: medium
    has_border: true
    background_color: none
    background_image: images/pattern.svg
    background_image_repeat: repeat
    background_image_size: auto
    background_image_opacity: 98
  - type: grid_section
    title: Subscribe
    grid_items:
      - title: Overcast
        title_align: center
        content_align: center
        actions:
          - label: Subscribe
            url: /thank-you
            style: secondary
            has_icon: true
            icon: arrow-right
            icon_position: right
        actions_align: center
        image: images/icon-3.svg
        image_alt: Overcast icon
        image_position: top
        image_align: center
        image_has_padding: true
    grid_cols: three
    grid_gap_horiz: medium
    grid_gap_vert: medium
    enable_cards: false
    align: center
    padding_top: large
    padding_bottom: large
    has_border: true
    background_color: secondary
    background_image: images/subscribe-background.jpg
    background_image_repeat: no-repeat
    background_image_size: cover
    background_image_opacity: 10
  - type: form_section
    content: >-
      ## Ask A Question

      I'm OK with any kind of questions and will answer as many as I possibly
      can.
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: inline
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: textarea
        name: message
        label: Question
        default_value: Your question
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Submit
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: none
    background_image_repeat: repeat
    background_image_size: auto
    background_image_opacity: 98
seo:
  title: Stackbit Podcaster Theme
  description: The preview of the Podcaster theme
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Stackbit Podcaster Theme
      keyName: property
    - name: 'og:description'
      value: The preview of the Podcaster theme
      keyName: property
    - name: 'og:image'
      value: images/hero.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Stackbit Podcaster Theme
    - name: 'twitter:description'
      value: The preview of the Podcaster theme
    - name: 'twitter:image'
      value: images/hero.png
      relativeUrl: true
layout: advanced
---
