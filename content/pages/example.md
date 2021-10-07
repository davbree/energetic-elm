---
title: Example Page
layout: PageLayout
sections:
  - elementId: ''
    colors: colors-a
    width: wide
    height: tall
    topGap: medium
    bottomGap: medium
    contentWidth: large
    contentAlignHoriz: left
    contentAlignVert: middle
    textAlign: left
    variant: variant-a
    badge:
      elementId: ''
      label: lorem-ipsum
    title: About us
    subtitle: Meet the team
    actions: []
    people:
      - content/data/team/desmond-eagle.json
      - content/data/team/dianne-ameter.json
      - content/data/team/hilary-ouse.json
    type: FeaturedPeopleSection
  - elementId: ''
    colors: colors-h
    width: wide
    height: tall
    contentWidth: large
    contentAlignHoriz: center
    contentAlignVert: middle
    topGap: none
    bottomGap: none
    textAlign: left
    variant: variant-b
    badge:
      elementId: ''
      label: lorem-ipsum
    title: lorem-ipsum
    text: >-
      ## Lorem ipsum


      Lorem ipsum dolor sit amet, **consectetur adipiscing elit**, sed do
      eiusmod tempor incididunt ut labore et dolore magna aliqua.


      - Lorem ipsum

      - dolor sit amet
    form:
      type: FormBlock
      idAttr: contact-form
      action: /.netlify/functions/submission_created
      destination: ''
      fields:
        - type: TextFormControl
          name: name
          label: Name
          placeholder: Your name
          isRequired: true
          width: 1/2
        - type: EmailFormControl
          name: email
          label: Email
          placeholder: Your email
          isRequired: true
          width: 1/2
        - type: TextFormControl
          name: home-address
          label: Home address
          placeholder: Your home address
          isRequired: true
          width: full
        - type: CheckboxFormControl
          name: updates
          label: Sign me up to receive updates
          width: full
      submitLabel: Send Message
    feature:
      type: ImageBlock
      url: /images/contact.png
      altText: Contact form image
    type: ContactSection
  - type: QuoteSection
    colors: colors-c
    width: wide
    height: short
    textAlign: left
    quote: >-
      Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium
      doloremque laudantium, totam rem aperiam. Eaque ipsa quae ab illo
      inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.
      Sed ut perspiciatis undeomnis iste natus error sit voluptatem accusantium
      doloremque laudantium, totam rem aperiam. Eaque ipsa quae ab illo
      inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.
    name: Isabelle Parks
    title: Head chef at The Cook
    backgroundImage:
      type: ImageBlock
      url: /images/water.jpg
      altText: Water
      caption: ''
      opacity: 40
---
