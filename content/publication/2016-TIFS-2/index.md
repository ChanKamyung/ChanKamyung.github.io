---
title: "Server-Aided Public Key Encryption With Keyword Search"
authors:
- admin
- Yi Mu
- Guomin Yang
- Fuchun Guo
- Xinyi Huang
- Xiaofen Wang
- Yongjun Wang

date: "2016-08-10T00:00:00Z"
doi: "10.1109/TIFS.2016.2599293"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Information Forensics and Security*"
publication_short: "*TIFS*"

abstract: "<p>Public key encryption with keyword search (PEKS) is a well-known cryptographic primitive for secure searchable data encryption in cloud storage. Unfortunately, it is inherently subject to the (inside) offline keyword guessing attack (KGA), which is against the data privacy of users. Existing countermeasures for dealing with this security issue mainly suffer from low efficiency and are impractical for real applications. In this paper, we provide a practical and applicable treatment on this security vulnerability by formalizing a new PEKS system named server-aided public key encryption with keyword search (SA-PEKS). In SA-PEKS, to generate the keyword ciphertext/trapdoor, the user needs to query a semitrusted third-party called keyword server (KS) by running an authentication protocol, and hence, security against the offline KGA can be obtained. We then introduce a universal transformation from any PEKS scheme to a secure SA-PEKS scheme using the deterministic blind signature. To illustrate its feasibility, we present the first instantiation of SA-PEKS scheme by utilizing the Full Domain Hash RSA signature and the PEKS scheme proposed by Boneh et al. in Eurocrypt 2004. Finally, we describe how to securely implement the client-KS protocol with a rate-limiting mechanism against online KGA and evaluate the performance of our solutions in experiments.</p>"

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Cryptographic Approaches for Data Security
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
  caption: 'Fig.1 **System model of Server-Aided PEKS**'
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


