---
title: "Strongly Leakage-Resilient Authenticated Key Exchange"
authors:
- admin
- Yi Mu
- Guomin Yang
- Willy Susilo
- Fuchun Guo

date: "2016-02-29T00:00:00Z"
doi: "10.1007/978-3-319-29485-8_2"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *The Cryptographer's Track at the RSA Conference 2016*
publication_short: In *CT-RSA 2016*

abstract: "<p>Authenticated Key Exchange (AKE) protocols have been
widely deployed in many real-world applications for securing communication
channels. In this paper, we make the following contributions. First,
we revisit the security modelling of leakage-resilient AKE protocols, and
show that the existing models either impose some unnatural restrictions
or do not sufficiently capture leakage attacks in reality.We then introduce
a new strong yet meaningful security model, named challenge-dependent
leakage-resilient eCK (CLR-eCK) model, to capture challenge-dependent
leakage attacks on both long-term secret key and ephemeral secret key
(i.e., randomness). Second, we propose a general framework for constructing
one-round CLR-eCK-secure AKE protocols based on smooth projective
hash functions (SPHFs). Finally, we present a practical instantiation
of the general framework based on the Decisional Diffie-Hellman assumption
without random oracle. Our result shows that the instantiation is
efficient in terms of the communication and computation overhead and
captures more general leakage attacks.</p>"

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Provable-Security Cryptography
featured: true
featured_first: true
featured_second: false

#links:
#- name: Custom Link
#  url: http://example.org
#url_pdf: '#'
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Fig.1 **Framework for CLR-eCK secure AKE**'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: ""
---
