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


      ### Asunción PY

      una calle.
      asuncion, CA 12345
      021 123456 0971123456
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: nameTuT
        label: Nombre
        default_value: Su numbre
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Su correo electrónico
        is_required: true
      - input_type: select
        name: subject
        label: Que servicios estas buscando?
        default_value: Por favor seleccione
        options:
          - Marca
          - Diseño
          - Análisis
      - input_type: textarea
        name: message
        label: Mensaje
        default_value: Su mensaje
      - input_type: checkbox
        name: consent
        label: >-
          Entiendo que este formulario está almacenando mi información enviada
          para que puedan ser contactados.
    submit_label: Enviar
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
