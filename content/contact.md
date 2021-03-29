---
title: Contact
sections:
  - section_id: contact
    type: section_contact
    background: gray
    title: Contact
    content: >
      ​​We are a humanitarian voluntary charity that has provided the new
      experimental drug RCH4, always free of charge, for some years worldwide to
      PALS (Persons with ALS also known as MND).


      Having no external source of support and critically short of funding, this
      contact us page only appears intermittently.
    form_id: contactForm
    form_fields:
      - input_type: text
        name: name
        label: Name
        is_required: true
      - input_type: email
        name: email
        label: Email
        is_required: true
      - input_type: select
        name: subject
        label: Subject
        default_value: Please select
        options:
          - Error on the site
          - Requesting the drug
        is_required: true
      - input_type: textarea
        name: message
        label: Message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Send Message
    hide_labels: false
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
      value: summary_large_image
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: landing
---
