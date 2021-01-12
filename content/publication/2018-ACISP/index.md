---
title: "Asymmetric Subversion Attacks on Signature Schemes"
authors:
- Chi Liu
- admin
- Yi Wang
- Yongjun Wang

author_notes:
- ""
- "Corresponding author"
- ""
- "Corresponding author"

date: "2018-06-13T00:00:00Z"
doi: "10.1007/978-3-319-93638-3_22"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *23rd Australasia Conference on Information Security and Privacy*
publication_short: In *ACISP 2018*

abstract: "Subversion attacks against cryptosystems have already received wide attentions since several decades ago, while the Snowden revelations in 2013 reemphasized the need to further exploring potential avenues for undermining the cryptography in practice. In this work, inspired by the kleptographic attacks introduced by Young and Yung in 1990s [Crypto’96], we initiate a formal study of asymmetric subversion attacks against signature schemes. Our contributions can be summarized as follows.
<ul>
	<li> We provide a formal definition of asymmetric subversion model for signature schemes. Our asymmetric model improves the existing symmetric subversion model proposed by Ateniese, Magri and Venturi [CCS’15] in the sense that the undetectability is strengthened and the signing key recoverability is defined as a strong subversion attack goal.</li>
	<li> We introduce a special type of signature schemes that are splittable
and show how to universally mount the subversion attack against
such signature schemes in the asymmetric subversion model. Compared
with the symmetric attacks introduced by Ateniese, Magri and
Venturi [CCS’15], our proposed attack enables much more efficient
key recovery that is independent of the signing key size. </li>
</ul>
Our asymmetric subversion framework is somewhat conceptually simple
but well demonstrates that subversion attacks against signature schemes
could be quite practical, and thus increases awareness and spurs the
search for deterrents."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Subversion-Resilient Cryptography
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
  caption: 'Fig.1 **A universal AS-SA on<br/>splittable signature scheme**'
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
