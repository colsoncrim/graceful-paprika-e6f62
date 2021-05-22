---
title: Home
sections:
  - type: hero_section
    title: 'Design. Build. Deploy.'
    subtitle: >-
      JAMstack developer making fast, scalable, and maintainable websites. I'm an experienced developer, leveraging modern technologies to create products that users love.
    actions:
      - label: Contact Me
        url: /contact
        style: primary
    image: images/code_hero_2.png
    image_alt: Responsive website
    media_position: right
    media_width: fifty
    align: left
    padding_top: large
    padding_bottom: large
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
  - type: features_section
    title: My Projects
    subtitle: See what I've been up to
    features:
      - title: Optimal Strength
        subtitle: 'Template website for CrossFit gym'
        content: >-
          This template website was made with HTML, CSS, and React. It features
          a mobile-friendly, responsive design with custom components. It's
          simple layout makes for a great starter for anyone looking to get a head
          start on building out their website.
        actions:
          - label: View Project
            url: /coming-soon
            style: primary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: images/project_1.png
        image_alt: Project 1 illustration
        media_position: right
        media_width: sixty
      - title: Stackbit Example 2
        subtitle: 'Product updates, inventory and pricing.'
        content: >-
          Managing an online business is a full-time job. I will make sure your
          products look great, sound great, and sell more on your choice of
          ecommerce platform.
        actions:
          - label: View Project
            url: /coming-soon
            style: secondary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: images/project_3.png
        image_alt: Project 2 illustration
        media_position: right
        media_width: sixty
      - title: Coding Blog
        subtitle: 'Example blog website using modern JAMstack technologies.'
        content: >-
          JAMstack website built with Gatsby and React. Uses GraphQL to query markdown files to pull in data for each blog post.
        actions:
          - label: View Project
            url: https://gatsby-coding-blog.netlify.app/
            style: primary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: images/coding_blog.png
        image_alt: Blog screenshot
        media_position: right
        media_width: sixty
    feature_padding_vert: large
    align: center
    background_color: none
  - type: grid_section
    title: Tech Stack
    subtitle: Technologies I use
    align: center
    grid_items:
      - image: images/Gatsby_Logo.svg
        image_alt: Gatsby
        image_align: center
      - image: images/netlify_logo_3.png
        image_alt: Netlify
        image_align: center
      - image: images/react_3.png
        image_alt: React
        image_align: center
      - image: images/strapi_logo.svg
        image_alt: Strapi
        image_align: center
    grid_cols: four
    grid_gap_horiz: medium
    grid_gap_vert: medium
  - type: form_section
    content: >-
      ## Let's talk


      If you have any questions, please fill out this form and I will get in touch with you as soon as I can.
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: stacked
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
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Send Message
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
seo:
  title: Colson Crim | JAMstack developer
  description: colsoncrim.dev
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Colson Crim | JAMstack developer
      keyName: property
    - name: 'og:description'
      value: colsoncrim.dev
      keyName: property
    - name: 'og:image'
      value: images/personal-preview.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Colson Crim | JAMstack developer
    - name: 'twitter:description'
      value: colsoncrim.dev
    - name: 'twitter:image'
      value: images/personal-preview.png
      relativeUrl: true
template: advanced
---
