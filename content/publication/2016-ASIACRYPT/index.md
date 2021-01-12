---
title: "Cryptographic Reverse Firewall via Malleable Smooth Projective Hash Functions"
authors:
- admin
- Yi Mu
- Guomin Yang
- Willy Susilo
- Fuchun Guo
- Mingwu Zhang

date: "2016-12-04T00:00:00Z"
doi: "10.1007/978-3-662-53887-6_31"

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

abstract: "Motivated by the revelations of Edward Snowden, post-
Snowden cryptography has become a prominent research direction in
recent years. In Eurocrypt 2015, Mironov and Stephens-Davidowitz proposed
a novel concept named <i>cryptographic reverse firewall</i> (CRF) which
can resist exfiltration of secret information from an arbitrarily compromised
machine. In this work, we continue this line of research and present
generic CRF constructions for several widely used cryptographic protocols
based on a new notion named <i>malleable smooth projective hash function</i>.
Our contributions can be summarized as follows.<ul>
<li> We introduce the notion of malleable smooth projective hash function,
which is an extension of the smooth projective hash function
(SPHF) introduced by Cramer and Shoup (Eurocrypt’02) with the
new properties of <i>key malleability</i> and <i>element rerandomizability</i>. We
demonstrate the feasibility of our new notion using graded rings proposed
by Benhamouda et al. (Crypto’13), and present an instantiation
from the <i>k</i>-linear assumption.</li>
<li> We show how to generically construct CRFs via malleable SPHFs in
a modular way for some widely used cryptographic protocols. Specifically,
we propose generic constructions of CRFs for the unkeyed
message-transmission protocol and the oblivious signature-based envelope
(OSBE) protocol of Blazy, Pointcheval and Vergnaud (TCC’12).
We also present a new malleable SPHF from the linear encryption of
valid signatures for instantiating the OSBE protocol with CRFs.</li>
<li> We further study the two-pass oblivious transfer (OT) protocol and
show that the malleable SPHF does not suffice for its CRF constructions.
We then develop a new OT framework from graded rings and
show how to construct OT-CRFs by modifying the malleable SPHF
framework. This new framework encompasses the DDH-based OT-CRF
constructions proposed by Mironov and Stephens-Davidowitz (Eurocrypt’
15), and yields a new construction under the <i>k</i>-linear assumption.</li></ul>"

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Subversion-Resilient Cryptography
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
  caption: '**Oblivious Transfer with CRFs**'
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
