---
title: IEEE Symposium on Computers and Communications (ISCC) 2025

event: Presentation at 30th IEEE Symposium on Computers and Communications (ISCC)
event_url: https://ieee-iscc.computer.org/2025/ 

location: Bologna, Italy

summary: Presented my research as a paper author at the IEEE International Symposium on Computers and Communications (ISCC).
abstract: |
  Remote Attestation (RA) is a security process that verifies the integrity and trustworthiness of a remote device's software and hardware. While RA for high-end devices is well-developed, RA in constrained IoT environments remains incomplete. Existing embedded RA mechanisms focus on local evidence generation and verification, but lack a complete process that includes a secure attestation channel. This paper introduces AuRA, a lightweight RA solution that builds upon the newly standardized Ephemeral Diffie-Hellman over COSE (EDHOC) protocol. AuRA specifies how to transport existing attestation mechanisms in parallel with network authentication. We evaluate AuRA on the nRF5340 microcontroller running at 64 MHz. This implementation has a memory footprint of 6,665 B of RAM and 17,163 B of flash. The device completes Remote Attestation by exchanging three EDHOC messages with a verifier entity, of sizes 42 B, 59 B and 223 B. This allows the device to prove that it is running the right hardware and software in only 5.51 s, consuming as little as 88 mC of charge.

date: '2025-07-02'
date_end: '2025-07-05'
all_day: true

# Schedule page publish date (NOT talk date).
#publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags: [Remote Attestation, Authentication Protocol, Security in IoT]

# Is this a featured talk? (true/false)
featured: false

image:
  caption: ''
  focal_point: Right

share: false
reading_time: false

# links:
#   - type: code
#     url: https://github.com
#   - type: slides
#     url: https://slideshare.net
#   - type: video
#     url: https://youtube.com

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - example
---
![ISCC photo](isccpres.png)
![ISCC photo](isccpres2.png)
![ISCC photo](iscchotel.png)
<!-- > [!NOTE]
> Click on the **Slides** button above to view the built-in slides feature.

Slides can be added in a few ways:

- **Create** slides using Hugo Blox Builder's [_Slides_](https://docs.hugoblox.com/reference/content-types/) feature and link using the `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to this page bundle and link it using `links: [{ type: slides, url: path/to/file } ]` in front matter
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/reference/markdown/).

Further event details, including [page elements](https://docs.hugoblox.com/reference/markdown/) such as image galleries, can be added to the body of this page. -->
