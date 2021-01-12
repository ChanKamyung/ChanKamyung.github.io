---
title: "Recipient Revocable Identity-Based Broadcast Encryption: How to Revoke
               Some Recipients in IBBE without Knowledge of the Plaintext"
authors:
- Willy Susilo
- admin
- Fuchun Guo
- Guomin Yang
- Yi Mu
- Yang-Wai Chow

date: "2016-06-01T00:00:00Z"
doi: "10.1145/2897845.2897848"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *11th Asia Conference on Computer and Communications Security*
publication_short: In *ASIACCS 2016*

abstract: "<p>In this paper, we present the notion of recipient-revocable identity-based broadcast encryption scheme. In this notion, a content provider will produce encrypted content and send them to a third party (which is a broadcaster). This third party will be able to revoke some identities from the ciphertext. We present a security model to capture these requirements, as well as a concrete construction. The ciphertext consists of k + 3 group elements, assuming that the maximum number of revocation identities is k. That is, the ciphertext size is linear in the maximal size of R, where R is the revocation identity set. However, we say that the additional elements compared to that from an IBBE scheme are only for the revocation but not for decryption. Therefore, the ciphertext sent to the users for decryption will be of constant size (i.e.,3 group elements). Finally, we present the proof of security of our construction.</p>"

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Provable-Security Cryptography
featured: false

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
  caption: ""
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
