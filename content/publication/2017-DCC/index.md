---
title: "Strong Authenticated Key Exchange with Auxiliary Inputs"
authors:
- admin
- Yi Mu
- Guomin Yang
- Willy Susilo
- Fuchun Guo

date: "2016-11-02T00:00:00Z"
doi: "10.1007/s10623-016-0295-3"

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

abstract: Leakage attacks, including various kinds of side-channel attacks, allow an attacker to learn partial information about the internal secrets such as the secret key and the randomness of a cryptographic system. Designing a strong, meaningful, yet achievable security notion to capture practical leakage attacks is one of the primary goals of leakage-resilient cryptography. In this work, we revisit the modelling and design of authenticated key exchange (AKE) protocols with leakage resilience. We show that the prior works on this topic are inadequate in capturing realistic leakage attacks. To close this research gap, we propose a new security notion named leakage-resilient eCK model w.r.t. auxiliary inputs ($\texttt{AI-LR-eCK}$) for AKE protocols, which addresses the limitations of the previous models. Our model allows computationally hard-to-invert leakage of both the long-term secret key and the randomness, and also addresses a limitation existing in most of the previous models where the adversary is disallowed to make leakage queries during the challenge session. As another major contribution of this work, we present a generic framework for the construction of AKE protocols that are secure under the proposed $\texttt{AI-LR-eCK}$ model. An instantiation based on the decision Diffie–Hellman (DDH) assumption in the standard model is also given to demonstrate the feasibility of our proposed framework.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Provable-Security Cryptography
featured: true
featured_first: true
featured_second: false

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
  caption: 'Tab.1 **Comparison with existing leakage-resilient AKE security models**'
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


