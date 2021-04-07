---
draft: false
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


      If you wish to contact us, kindly study the following


      If applying for help on behalf of someone else, please state their first,
      given, name along with your own name.  

      Your information is confidential and will never be shared with any other
      party.
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
      - input_type: number
        name: age
        label: What is your age in years?
        options: []
        is_required: false
        type: form_field
      - input_type: text
        name: occupation
        label: 'What is, or was, your occupation or profession?'
        options: []
        is_required: false
        type: form_field
      - input_type: select
        label: Do you have a written diagnosis of ALS or MND?
        default_value: 'yes'
        options:
          - 'no'
        is_required: false
        type: form_field
        name: diagnosis
      - input_type: number
        name: diagnosis-months
        label: How many months since that diagnosis?
        options: []
        is_required: false
        type: form_field
      - input_type: number
        name: onset-months
        label: >-
          How many months since you think or believe that your ALS symptoms
          started?
        options: []
        is_required: false
        type: form_field
      - input_type: select
        name: neurologist
        label: Is your doctor a recognised Neurologist?
        default_value: 'yes'
        options:
          - 'no'
        is_required: true
        type: form_field
      - input_type: text
        name: ALSFRS-R-score
        label: >-
          Have you been told what your ALSFRS-R score is, and if so, what is it
          and when?
        options: []
        is_required: false
        type: form_field
      - input_type: select
        name: radicava
        label: Do you take Edaravone (Radicava)?
        default_value: 'yes'
        options:
          - 'no'
        is_required: true
        type: form_field
      - input_type: textarea
        name: health
        label: What other serious health condition/s do you have?
        options: []
        is_required: false
        type: form_field
      - input_type: textarea
        name: alergies
        label: 'Are you allergic to anything, e.g., drugs, foods, nuts, pollen, etc.?'
        options: []
        is_required: false
        type: form_field
      - input_type: textarea
        name: message
        label: Message
        options: []
      - input_type: select
        name: blood-test
        label: Do you have a recent full blood test available?
        default_value: 'yes'
        options:
          - 'no'
        is_required: true
        type: form_field
      - input_type: select
        name: care-giver
        label: 'Do you live with a care giver (spouse, family, etc)?'
        default_value: 'yes'
        options:
          - 'no'
        is_required: false
        type: form_field
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
      - input_type: textarea
        name: children
        label: >-
          Do you have children under the age of 18 years? If so, what are their
          ages?
        options: []
        is_required: false
        type: form_field
      - input_type: textarea
        name: familial
        label: >-
          Does any relative of yours have or had ALS? If so, state relationship
          (sibling, cousin etc.)
        options: []
        is_required: false
        type: form_field
      - input_type: text
        name: country
        label: What country do you live in?
        default_value: lorem-ipsum
        options: []
        is_required: false
        type: form_field
    submit_label: Send Message
    hide_labels: false
    form_action: 'https://formspree.io/f/myylgvzr'
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
