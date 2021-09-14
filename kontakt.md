---
title: Kontakt
hide_title: false
sections:
  - type: form_section
    section_id: contact-form
    content: >-
      Sie möchten noch mehr wissen?<br>

      Senden Sie mir einfach über das Formular rechts eine Email!

      ***


      ## Mein Studio


      ### Raum für Begegnung

      Scheidter Str. 62<br>

      66123 Saarbrücken<br>

      0173 360 666 5<br>

      [Get directions &rarr;](https://goo.gl/maps/eh6fn7JjMS4vYs337)


      ### New York

      1234 Some St.<br>

      New York, NY 12345<br>

      1-234-556-7890<br>

      [Get directions &rarr;](https://goo.gl/maps/eh6fn7JjMS4vYs337)
    form_id: contactForm
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
      - input_type: select
        name: subject
        label: What services are you looking for?
        default_value: Please select
        options:
          - Branding
          - Design
          - Digital
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
    submit_label: Send Message
seo:
  title: Contact
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: advanced
---