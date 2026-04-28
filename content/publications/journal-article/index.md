---
title: "M-AuRA: Mutual Authentication and Remote Attestation over EDHOC"
authors:
- admin
- Elsa Lopez Perez
- Geovane Fedrecheski
- Thomas Watteyne
- Malisa Vucinic

# # author_notes:
# # - "Equal contribution"
# # - "Equal contribution"
date: "2026-01-01T00:00:00Z"

# # Schedule page publish date (NOT publication's date).
# publishDate: "2026-06-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Computers*
publication_short: In *IEEE Transactions on Computers*

abstract: >-
  The proliferation of Internet-of-Things (IoT) devices in critical infrastructure requires robust security mechanisms to verify device integrity and trustworthiness. Remote Attestation (RA) is a security mechanism for validating the software and hardware state of remote devices. Existing RA solutions for resource-constrained IoT devices lack comprehensive frameworks for secure attestation channels and focus primarily on local evidence generation without addressing end-to-end security. This paper introduces M-AuRA, a lightweight RA solution that fills these gaps by leveraging the newly standardized Ephemeral Diffie-Hellman over COSE (EDHOC) protocol. M-AuRA seamlessly integrates attestation with authentication, enabling both unilateral and mutual attestation modes while maintaining minimal resource overhead. Our framework specifies how to transport existing attestation mechanisms in parallel with secure communication establishment, providing a complete end-to-end security solution for IoT deployments. We demonstrate MAuRA’s practicality through implementation on the nRF5340 microcontroller running at 64 MHz, evaluating performance across both software and hardware cryptographic back-ends. In mutual attestation mode, our implementation consumes only 4,692 B RAM and 19,350 B flash memory usage, occupying 0.9% and 1.85% of available nRF5340 resources, respectively. The four-message EDHOC exchange (45 B, 65 B, 177 B and
  120 B) enables mutual trustworthiness verification in 10.46 s using software-based cryptographic back-end, or only 0.43 s with hardware acceleration, consuming 171.43 mC and 7.97 mC of charge, respectively.
# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
# - Source Themes
# featured: false

# hugoblox:
#   ids:
#     arxiv: 1512.04133v1

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

# Display this page in the Featured widget?
featured: true
share: false
reading_time: false

# Custom links
links:
   - type: doi
     url: "https://doi.ieeecomputersociety.org/10.1109/TC.2026.3678614"

# # Associated Projects (optional).
# #   Associate this publication with one or more of your projects.
# #   Simply enter your project's folder or file name without extension.
# #   E.g. `internal-project` references `content/project/internal-project/index.md`.
# #   Otherwise, set `projects: []`.
# projects: []

# # Slides (optional).
# #   Associate this publication with Markdown slides.
# #   Simply enter your slide deck's filename without extension.
# #   E.g. `slides: "example"` references `content/slides/example/index.md`.
# #   Otherwise, set `slides: ""`.
# slides: ""
---
