---
title: "Fully Privacy-Preserving ID-Based Broadcast Encryption with Authorization"
authors:
- Jianchang Lai
- Yi Mu
- Fuchun Guo
- admin

date: "2017-06-07T00:00:00Z"
doi: "10.1093/comjnl/bxx060"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*The Computer Journal*"
publication_short: "*TCJ*"

abstract: "<p>A revocable ID-based broadcast encryption scheme allows an authorized third party to revoke any receiver (decryptor) from the initial receiver set S of the original broadcast ciphertext without the need of decryption. However, the existing revocable ID-based broadcast encryption schemes in the literature cannot fully preserve the receiver privacy and have a large size of ciphertext when the revoked user sets are large. To solve these problems, in this paper, we propose a novel scheme: fully privacy-preserving ID-based broadcast encryption with authorization. Our scheme allows an authorized party to dynamically handle the decryption rights of receivers via an authorized user set L without knowing the message and the identities of the initial receivers. Only those users who are both in S and L can decrypt the ciphertext successfully. The final ciphertext reveals nothing about the identity information of receivers and the authorized users. Our scheme achieves full collusion resistance and is applicable to anonymous data sharing where the receivers are decided by the authorized third party (or multiple authorized third parties) excluding the data owner. We show that our proposed scheme is provably secure under the defined security models in the random oracle model.</p>"

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Provable-Security Cryptography 
featured: false

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
  caption: 'Fig.1 **Motivation scenario**'
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


