---
title: Contact
type: landing
date: 2024-04-22

sections:
  - block: contact  # Assuming 'contact' is a valid block type in your theme
    content:
      title: 'Feel free to reach out ~'
      subtitle: ''  # If no subtitle is needed, this can be removed or left empty
      text: 'Contact me via email, phone, or through my social media channels.'  # Added a text content
      image: "uploads/NO_address.png"
      email: yuhan.wang@sed.ethz.ch
      phone: +41 798637237
      #appointment_url: 'https://calendly.com'  # Uncomment if you have an appointment URL
      address:
        street: Sonneggstrasse 5
        city: Zürich City
        region: ZH
        postcode: '8092'
        country: Switzerland
        country_code: CH
        link: https://www.google.com/maps/place/Sonneggstrasse+5,+8006+Z%C3%BCrich/@47.3785812,8.5446438,17z/data=!3m1!4b1!4m6!3m5!1s0x479aa0a6ff9ea61d:0x1f5b9d5a645c1289!8m2!3d47.3785776!4d8.5472187!16s%2Fg%2F11c2f9y632?entry=ttu
      directions: "Enter Building NO and take the stairs to the office 11.3 on Floor H (H 11.3)."
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/jyuhon1024'
        - icon: skype
          icon_pack: fab
          name: Skype Me
          link: 'skype:echo123?call'
       # - icon: video
       #   icon_pack: fas
       #   name: Zoom Me
       #   link: 'https://zoom.com'

      autolink: true
      
      form:
        provider: netlify
        formspree:
          id: null  # Set this to a valid Formspree ID if used, or leave as null if not used
        netlify:
          captcha: false
        
    design:
      columns: '1'
---
