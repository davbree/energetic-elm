---
title: Home
layout: PageLayout
sections:
  - elementId: ''
    colors: colors-f
    width: wide
    height: tall
    contentWidth: large
    contentAlignHoriz: center
    contentAlignVert: middle
    topGap: none
    bottomGap: none
    textAlign: left
    variant: variant-a
    badge:
      elementId: ''
      label: lorem-ipsum
    title: Another Title!
    subtitle: This Is Subtitle
    text: Hello
    actions:
      - label: hey
        url: 'https://www.stackbit.com'
    feature:
      type: ImageBlock
      url: /images/hero.png
      altText: Hero section image
    backgroundImage:
      elementId: ''
      altText: lorem-ipsum
      caption: lorem-ipsum
      opacity: 100
      type: ImageBlock
    type: HeroSection
  - elementId: ''
    colors: colors-f
    width: wide
    height: tall
    contentWidth: large
    contentAlignHoriz: center
    contentAlignVert: middle
    topGap: none
    bottomGap: none
    textAlign: left
    variant: variant-a
    badge:
      elementId: ''
      label: lorem-ipsum
    title: This Is A Big Hero Headline
    subtitle: This Is Subtitle
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
    actions:
      - type: Button
        label: Get Started
        url: /
        style: primary
        elementId: hero-main-button
      - type: Button
        label: Learn More
        url: /
        style: secondary
    feature:
      type: ImageBlock
      url: /images/hero.png
      altText: Hero section image
    backgroundImage:
      elementId: ''
      altText: lorem-ipsum
      caption: lorem-ipsum
      opacity: 100
      type: ImageBlock
    type: HeroSection
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
    variant: variant-b
    badge:
      elementId: ''
      label: lorem-ipsum
    title: Let's do this
    text: >-
      The Stackbit theme is flexible and scalable to every need. It can manage
      any layout and any screen.
    actions:
      - type: Button
        label: Try it now
        url: /about
        style: primary
    backgroundImage:
      elementId: ''
      altText: lorem-ipsum
      caption: lorem-ipsum
      opacity: 100
      type: ImageBlock
    type: CtaSection
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
    variant: variant-b
    badge:
      elementId: ''
      label: lorem-ipsum
    title: Let's do this
    text: >-
      The Stackbit theme is flexible and scalable to every need. It can manage
      any layout and any screen.
    actions:
      - type: Button
        label: Try it now
        url: /about
        style: primary
    backgroundImage:
      elementId: ''
      altText: lorem-ipsum
      caption: lorem-ipsum
      opacity: 100
      type: ImageBlock
    type: CtaSection
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
    variant: variant-b
    badge:
      elementId: ''
      label: lorem-ipsum
    title: Let's do this
    text: >-
      The Stackbit theme is flexible and scalable to every need. It can manage
      any layout and any screen.
    actions:
      - type: Button
        label: Try it now
        url: /about
        style: primary
    backgroundImage:
      elementId: ''
      altText: lorem-ipsum
      caption: lorem-ipsum
      opacity: 100
      type: ImageBlock
    type: CtaSection
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
    variant: variant-b
    badge:
      elementId: ''
      label: lorem-ipsum
    title: Latest news
    subtitle: Featured blog posts section example
    actions:
      - type: Button
        label: View all
        url: /
        style: primary
    posts:
      - content/pages/blog/post-three.md
      - content/pages/blog/post-two.md
      - content/pages/blog/post-one.md
    type: FeaturedPostsSection
  - type: ContactSection
    variant: variant-b
    colors: colors-h
    width: wide
    height: tall
    textAlign: left
    title: Join our club
    bottomGap: none
    topGap: none
    text: >-
      We will notify you every time a shipment is heading to your neighborhood,
      and you could immediatly let us know if you want in or not.
    feature:
      type: ImageBlock
      url: /images/contact.png
      altText: Fisherman holding lobster
    form:
      type: FormBlock
      idAttr: contact-form
      destination: ''
      action: /.netlify/functions/submission_created
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
---
