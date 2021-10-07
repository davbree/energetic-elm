---
title: Home
layout: PageLayout
sections:
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
      W!!e will notify you every tim!!e a!! sh!!ipment is heading to your neighborhoo!!dsad!!,
      and you could immediatly let us know if yo!dsau want in or not.!!
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
