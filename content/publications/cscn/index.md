---
title: 'When to Attest? Intra- and Post-Handshake Attestation for IoT Swarms'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Muhammad Usama Sardar
  - Geovane Fedrecheski
  - Malisa Vucinic
  - Thomas Watteyne

date: "2025-09-15T00:00:00Z"

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Conference on Standards for Communications and Networking (CSCN)*
publication_short: In *IEEE Conference on Standards for Communications and Networking (CSCN)*

abstract: |
  Remote attestation is a security mechanism that allows a device to prove its integrity and trustworthiness by generating fresh verifiable evidence to be assessed by a verifier. It is gaining increasing attention in the context of IoT security for both IoT devices and services. Within the ongoing standardization efforts at the IETF, two distinct approaches have emerged and are actively discussed by different working groups and protocol designers: (1) intra-handshake attestation, where attestation is performed during the handshake process; (2) posthandshake attestation, where it occurs after the handshake is complete. This position paper analyzes the respective security properties and discusses their applicability across different IoT deployment scenarios. We highlight the key trade-off: intrahandshake attestation enables early trust establishment prior to session setup, making it suitable for onboarding scenarios, while post-handshake attestation provides continuous assurance and supports runtime integrity validation.


# Display this page in the Featured widget?
featured: true
share: false
reading_time: false

# Custom links
links:
  - type: pdf
    url: "conference-paper.pdf"


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

---