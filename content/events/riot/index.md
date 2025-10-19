---
title: Invited Speaker at RIOT Summit 2024

event: RIOT Summit 2024
event_url: https://summit.riot-os.org/2024/ 

location: Vienna, Austria

summary: Invited to give a talk on 'Lightweight remote attestation over EDHOC for constrained IoT devices' at RIOT Summit 2024.
abstract: | 
  In this talk, we proposed a new idea to explore the possibility of applying remote attestation on ecosystems such as RIOT OS. The talk is based on an Internet-Draft published at the IETF LAKE working group, which is named 'Remote attestation over EDHOC'.<br><br>

  We developed an efficient method of performing remote attestation in parallel with network access authentication, utilizing a newly standardized key exchange protocol named Ephemeral Diffie-Hellman Over COSE (EDHOC). EDHOC is very compact and lightweight, making it suitable for constrained environments. Remote attestation is a security service that remotely verifies and confirms the integrity and trustworthiness of devices. One use case, and the focus of our current implementation on a micro-robot, is the onboarding check process, where a constrained IoT device must prove its trustworthiness to establish a level of trust on a remote server and gain network access.<br><br>

  Yuxuan presented the detailed procedures of how attestation items are carried as external authentication data over the EDHOC protocol to achieve attestation in parallel with network authentication. Additionally, an open discussion on the applicability of this approach for RIOT OS was included.

date: '2024-09-05'
date_end: '2024-09-07'
all_day: true

# Schedule page publish date (NOT talk date).
#publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags: [RIOT OS, Access Control, Lightweight Attestation]

# Is this a featured talk? (true/false)
featured: false

image:
  caption: ''
  focal_point: Right

share: false
reading_time: false

links:
#   - type: code
#     url: https://github.com
  # - type: slides
  #   url: https://openwsn.atlassian.net/wiki/spaces/~712020ee5b129a44b54c67a172544eca851fe6/pages/2716008455/RIOT+Summit+2024 
  - type: video
    url: https://www.youtube.com/watch?v=qViyE783FTE&t=1177s 

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
<!-- > [!NOTE]
> Click on the **Slides** button above to view the built-in slides feature.

Slides can be added in a few ways:

- **Create** slides using Hugo Blox Builder's [_Slides_](https://docs.hugoblox.com/reference/content-types/) feature and link using the `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to this page bundle and link it using `links: [{ type: slides, url: path/to/file } ]` in front matter
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/reference/markdown/).

Further event details, including [page elements](https://docs.hugoblox.com/reference/markdown/) such as image galleries, can be added to the body of this page. -->
