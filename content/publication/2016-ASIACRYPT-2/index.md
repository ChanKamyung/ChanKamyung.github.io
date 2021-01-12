---
title: "Iterated Random Oracle: A Universal Approach for Finding Loss in Security Reduction"
authors:
- Fuchun Guo
- Willy Susilo
- Yi Mu
- admin
- Jianchang Lai
- Guomin Yang

date: "2016-12-04T00:00:00Z"
doi: "10.1007/978-3-662-53890-6_25"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *22nd Annual International Conference on the Theory and Applications of Cryptology and Information Security*
publication_short: In *ASIACRYPT 2016*

abstract: The indistinguishability security of a public-key cryptosystem can be reduced to a computational hard assumption in the random oracle model, where the solution to a computational hard problem is hidden in one of the adversary’s queries to the random oracle. Usually, there is a *finding loss* in finding the correct solution from the query set, especially when the decisional variant of the computational problem is also hard. The problem of finding loss must be addressed towards tight(er) reductions under this type. In EUROCRYPT 2008, Cash, Kiltz and Shoup proposed a novel approach using a trapdoor test that can solve the finding loss problem. The simulator can find the correct solution with overwhelming probability $1$, if there exists a trapdoor test for the adopted hard problem. The proposed approach is efficient and can be used for many Diffie-Hellman computational assumptions. The only limitation is the requirement of a trapdoor test that must be found for the adopted computational assumptions.<br/>In this paper, we introduce a universal approach for finding loss, namely *Iterated Random Oracle*, which can be applied to all computational assumptions. The *finding loss* in our proposed approach is very small. For $2^{60}$ queries to the random oracle, the success probability of finding the correct solution from the query set will be as large as $1/64$ compared to $1/2^{60}$ by a random pick. We show how to apply the iterated random oracle for security transformation from key encapsulation mechanism with one-way security to normal encryption with indistinguishability security. The security reduction is very tight due to a small finding loss. The transformation does not expand the ciphertext size. We also give the application of the iterated random oracle in the key exchange.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Provable-Security Cryptography 
featured: true
featured_first: false
featured_second: true

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
  caption: 'Fig.5 **An example of arbitrary tree generated from iterated queries and responses**'
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
