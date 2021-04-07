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
        default_value: >-
          1/ Have you got a written diagnosis of ALS or MND?  
          2/ How many months since that diagnosis?
          3/ How many months since you think or believe that your ALS symptoms started? 4/ Is your doctor a recognised
          Neurologist? 5/ Have you been told what your ALSFRS-R score is, and if
          so, what is it and when? 6/ Do you take Edaravone (Radicava)? 7/ What
          other serious health condition/s do you have? 8/ Are you allergic to
          anything, e.g., drugs, foods, nuts, pollen, etc.? 9/ Your age in
          years? 10/ What is, or was, your occupation or profession? 11/ Do you
          have a recent full blood test available? 12/ Do you live with a care
          giver (spouse, family, etc)? 13/ Do you have children under the age of
          18 years? If so, what are their ages. 14/ Does any relative of yours
          have or had ALS? If so, state relationship (sibling, cousin etc.)  15/
          What country do you live in?  16/ Initially, you are welcome to add
          brief/short comments about your history or situation.
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
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
