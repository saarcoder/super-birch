---
title: Kontakt
hide_title: false
sections:
  - type: form_section
    section_id: contact-form
    content: |
      Sie möchten noch mehr wissen?<br>
      Senden Sie mir einfach über das Formular rechts eine Email!

      ***

      ## Mein Studio

      ### Raum für Begegnung

      Scheidter Str. 62<br>
      66123 Saarbrücken<br>
      0173-360 666 5<br>
      [Anfahrt →](https://goo.gl/maps/duq43J3zudk)

      ### Evangelische Familienbildungsstätte

      Mainzer Str. 269<br>
      66121 Saarbrücken<br>
      [Anfahrt →](https://goo.gl/maps/83xotMyjPzG2)
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Ihr name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Ihre Email Adresse
        is_required: true
      - input_type: select
        name: subject
        label: Wonach suchen Sie?
        default_value: Bitte auswählen
        options:
          - Ayurveda-Beratung
          - Kursanmeldung
          - Newsletter
      - input_type: textarea
        name: message
        label: Nachricht
        default_value: Ihre Nachricht
      - input_type: checkbox
        name: consent
        label: >-
          Ich habe verstanden, dass mit diesem Formular meine Daten online übermittelt werden, damit ich kontaktiert werden kann.
    submit_label: Nachricht senden
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
