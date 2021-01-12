---
title: "Strongly leakage resilient authenticated key exchange, revisited"
authors:
- Guomin Yang
- admin
- Yi Mu
- Willy Susilo
- Fuchun Guo
- Jie Li

date: "2019-06-22T00:00:00Z"
doi: "10.1007/s10623-019-00656-3"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Designs, Codes and Cryptography*"
publication_short: "*DCC*"

abstract: "<p>Authenticated Key Exchange (AKE) protocols allow two (or multiple) parties to authenticate each other and agree on a common secret key, which is essential for establishing a secure communication channel over a public network. AKE protocols form a central component in many network security standards such as IPSec, TLS/SSL, and SSH. However, it has been demonstrated that many standardized AKE protocols are vulnerable to side-channel and key leakage attacks. In order to defend against such attacks, leakage resilient (LR-) AKE protocols have been proposed in the literature. Nevertheless, most of the existing LR-AKE protocols only focused on the resistance to long-term key leakage, while in reality leakage of ephemeral secret key (or randomness) can also occur due to various reasons such as the use of poor randomness sources or insecure pseudo-random number generators (PRNGs). In this paper, we revisit the strongly leakage resilient AKE protocol (CT-RSA’16) that aimed to resist challenge-dependent leakage on both long-term and ephemeral secret keys. We show that there is a security issue in the design of the protocol and propose an improved version that can fix the problem. In addition, we extend the protocol to a more general framework that can be efficiently instantiated under various assumptions, including hybrid instantiations that can resist key leakage attacks while preserving session key security against future quantum machines.</p>"

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Provable-Security Cryptography
featured: true
featured_first: false
featured_second: true

# links:
# - name: ""
#   url: ""
# url_pdf: http://arxiv.org/pdf/1512.04133v1
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Fig.1 **Side-channel/secret-leakage attacks against AKE**'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---


