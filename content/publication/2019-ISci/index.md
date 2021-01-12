---
title: "Identity-based revocation system: Enhanced security model and scalable bounded IBRS construction with short parameters"
authors:
- Peng Jiang
- Jianchang Lai
- Fuchun Guo
- Willy Susilo
- Man Ho Au
- Guomin Yang
- Yi Mu
- admin

date: "2018-09-10T00:00:00Z"
doi: "10.1016/j.ins.2018.09.020"

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

abstract: "Identity-based revocation system (IBRS) produces a ciphertext based on the revoked identities such that this ciphertext can only be decrypted by the private keys of non-revoked identities. IBRS can be classified into unbounded IBRS and bounded IBRS, depending on whether to set a maximal revocation number (e.g., N) or not. Compared to unbounded IBRS, existing bounded IBRS schemes have the advantage of short ciphertexts, however, they cannot support an increase of N and have to fix a large N to provide the revocation. This compromises the computational efficiency, which is linear in N. To bridge this gap, we are interested in exploring whether N can be dynamic. Precisely, N is initially set as a small number and increased into a larger one when more than N identities are revoked, while this increase does not affect other non-revoked users in the system. In this paper, motivated by the security of bounded IBRS with a dynamic N, we define an enhanced security model, which allows the corruption of any polynomial number (e.g., n) of private keys, independent of N. It augments existing security models by running different challenges when n ≤ N and n > N, respectively. The enhanced security model suits both unbounded IBRS and bounded IBRS with a general description that can be “empty” for unbounded IBRS or a special N for bounded IBRS. Then, we propose a scalable bounded IBRS scheme and are able to prove its security in an enhanced security model. The increase of N incurs no changing on all of the existing private keys and the only cost is a slight expansion of the master public keys. Our proposed scheme also has short ciphertexts and private keys, comparable to the state-of-the-art (bounded) IBRS schemes."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Cryptographic Protocols for Privacy-Oriented Applications
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
  caption: 'Fig.1 **Our basic IBRS scheme for one single revoked identity**'
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


