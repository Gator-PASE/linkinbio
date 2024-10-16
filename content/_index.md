---
title: 'LinkInBio'
date: 2024-10-12
type: landing

design:
  background:
    image:
      # Add your image background to `assets/media/`.
      filename: bg-ffflux.svg

sections:
  - block: resume-biography
    content:
      # The user's folder name in content/authors/
      username: admin
    design:
      biography:
        style: 'text-align: justify; font-size: 0.8em;'
        spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
          padding: ['20px', '0', '20px', '0']
  - block: cta-button-list
    content:
      # Need a custom icon?
      # Add an SVG image to the `assets/media/icons/` folder and reference it in the `icon` field below
      buttons:
        - text: Check out the PASE website!
          icon: "custom/percy"
          url: https://gator-pase.netlify.app/
        - text: Become a PASE Gator!
          icon: "custom/qualtrics"
          url:  https://ufl.qualtrics.com/jfe/form/SV_ewFhF3vrD2qodxQ
        - text: Join PASE on Slack!
          icon: "custom/slack"
          url:  https://join.slack.com/t/policyadvocac-blu4799/shared_invite/zt-2sqgon4ow-O0msj48Ujyd__QtJgzO8JA
        - text: Follow PASE on Instagram!
          icon: brands/instagram
          url:  https://www.instagram.com/Gator_PASE/
        - text: Follow PASE on LinkedIn!
          icon: brands/linkedin
          url:  https://linkedin.com/company/gator-pase
        - text: Follow PASE on YouTube!
          icon: brands/youtube
          url:  https://www.youtube.com/@Gator-PASE/
        - text: Follow PASE on Twitter!
          icon: brands/twitter
          url:  https://twitter.com/Gator_PASE
        - text: Follow PASE on GatorConnect!
          icon: 
          url:  https://orgs.studentinvolvement.ufl.edu/Organization/policy-advocacy-in-science-and-engineering
---
