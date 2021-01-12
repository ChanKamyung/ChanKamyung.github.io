---
title: "Privacy-enhanced remote data integrity checking with updatable timestamp"
authors:
- Tong Wu
- Guomin Yang
- Yi Mu
- admin
- Shengmin Xu

date: "2020-03-27T00:00:00Z"
doi: "10.1016/j.ins.2020.03.057"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Information Sciences*"
publication_short: "*ISCI*"

abstract: "Remote data integrity checking (RDIC) enables clients to verify whether the outsourced data is intact without keeping a copy locally or downloading it. Nevertheless, the existing RDIC schemes do not support the pay-as-you-go (PAYG) payment model, where the payment is decided by the volume and duration of the outsourced data. Specifically, none of the existing works have considered the client’s control over changes in storage duration. In this paper, we propose an RDIC scheme to simultaneously check the data content and storage duration represented by an updatable timestamp via the third-party auditor (TPA). Also, our proposed scheme achieves indistinguishable privacy (IND-privacy) against TPA for both data content and timestamp. To bind the content and timestamp in the authenticator and support efficient timestamp update, we construct the authenticator with the randomizable structure-preserving signature (SPS). Additionally, we utilize the Groth-Sahai proof and range proof to provide the IND-privacy and guarantee the timestamp validation in the auditing phase. We formalize the definition and security model and provide the formal proof of our scheme. We also present the theoretical and experimental performance analysis to demonstrate that our scheme is comparable to the previous RDIC schemes which do not consider the storage time."

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
  caption: 'Fig.1 **System architecture**'
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


