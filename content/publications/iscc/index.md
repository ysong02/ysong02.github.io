---
title: 'AuRA: Remote Attestation over EDHOC for Constrained Internet-of-Things Use Cases'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Geovane Fedrecheski
  - Malisa Vucinic
  - Thomas Watteyne

date: "2025-07-02T00:00:00Z"

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Symposium on Computers and Communications (ISCC)*
publication_short: In *IEEE Symposium on Computers and Communications (ISCC)*

abstract: |
  Remote Attestation (RA) is a security process that verifies the integrity and trustworthiness of a remote device's software and hardware. While RA for high-end devices is well-developed, RA in constrained IoT environments remains incomplete. Existing embedded RA mechanisms focus on local evidence generation and verification, but lack a complete process that includes a secure attestation channel. This paper introduces AuRA, a lightweight RA solution that builds upon the newly standardized Ephemeral Diffie-Hellman over COSE (EDHOC) protocol. AuRA specifies how to transport existing attestation mechanisms in parallel with network authentication. We evaluate AuRA on the nRF5340 microcontroller running at 64 MHz. This implementation has a memory footprint of 6,665 B of RAM and 17,163 B of flash. The device completes Remote Attestation by exchanging three EDHOC messages with a verifier entity, of sizes 42 B, 59 B and 223 B. This allows the device to prove that it is running the right hardware and software in only 5.51 s, consuming as little as 88 mC of charge.


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