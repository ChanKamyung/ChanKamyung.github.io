---
title: "Optimal Security Reductions for Unique Signatures: Bypassing Impossibilities with a Counterexample"
authors:
- Fuchun Guo
- admin
- Willy Susilo
- Jianchang Lai
- Guomin Yang
- Yi Mu

date: "2017-07-29T00:00:00Z"
doi: "10.1007/978-3-319-63715-0_1"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *37th Annual International Cryptology Conference*
publication_short: In *CRYPTO 2017*

abstract: <p>Optimal security reductions for unique signatures (Coron, Eurocrypt 2002) and their generalization, i.e., efficiently re-randomizable signatures (Hofheinz <i>et al.</i> PKC 2012 & Bader <i>et al.</i> Eurocrypt 2016) have been well studied in the literature. Particularly, it has been shown that under a non-interactive hard assumption, any security reduction (with or without random oracles) for a unique signature scheme or an efficiently re-randomizable signature scheme must loose a factor of at least $q_s$ in the security model of existential unforgeability against chosen-message attacks (EU-CMA), where $q_s$ denotes the number of signature queries. Note that the number $q_s$ can be as large as $2^{30}$ in practice. All unique signature schemes and efficiently re-randomizable signature schemes are concluded to be accompanied with loose reductions from these impossibility results.</p><p>Somewhat surprisingly, in contrast to previous impossibility results (Coron, Eurocrypt 2002; Hofheinz <i>et al.</i> PKC 2012; Bader <i>et al.</i> Eurocrypt 2016), in this work we show that without changing the assumption type and security model, it is not always the case that any security reduction must loose a factor of at least $q_s$. As a counterexample, we propose a unique signature scheme with a tight reduction in the EU-CMA security model under the Computational Diffie-Hellman (CDH) assumption. Precisely, in the random oracle model, we can program a security reduction with a loss factor of at most $nq^{1/n}$, where n can be any integer independent of the security parameter for the scheme construction and $q$ is the number of hash queries to random oracles. The loss factor in our reduction can be very small. Considering $n=25$ and $q=2^{50}$ as an example, the loss factor is of at most $nq^{1/n}=100$ and therefore our security reduction is tight.</p><p>Notice that the previous impossibility results are derived from proofs via a so-called meta-reduction technique. We stress that instead of indicating any flaw in their meta-reduction proofs, our counterexample merely demonstrates that their given meta-reduction proofs fail to capture all security reductions. More precisely, we adopt a reduction called <i>query-based reduction</i>, where the reduction uses a hash query from the adversary to solve an underlying hard problem. We show that the meta-reduction proofs break down in our query-based reduction. The query-based reduction is not a new notion and it has been adopted for encryption proofs, but this work is the first seminal approach for applying query-based reduction in digital signatures.</p><p>The given counterexample in this work is of an independent interest as it implies a generic way of constructing a digital signature scheme (including unique signatures) with a tight reduction in the random oracle model from a digital signature scheme with a loose reduction. Although our proposed methodology is somewhat impractical due to the inefficiency of signature length, it introduces a completely new approach for tight proofs that is different from traditional approaches using a random salt.</p>

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
