---
title: Contacto
hide_title: false
sections:
  - type: form_section
    section_id: contact-form
    content: |
      Construyamos algo maravilloso juntos
      Completa el formulario o enviános un correo a <email@example.com>.

      ***

      ## Nuestras oficinas

      ### Boqueron PY

      una calle.
      boqueron, CA 12345
      021 123456 0971123456
      [Get directions →](https://goo.gl/maps/eh6fn7JjMS4vYs337)

      ### Asunción PY

      una calle.
      asuncion, CA 12345
      021 123456 0971123456
      [Get directions →](https://goo.gl/maps/eh6fn7JjMS4vYs337)
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: nameTuT
        label: Nombre
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: select
        name: subject
        label: Que servicios estas buscando?
        default_value: Please select
        options:
          - Marca
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
