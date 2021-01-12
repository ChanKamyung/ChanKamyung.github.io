---
title: "Towards Practical Privacy-Preserving Decision Tree Training and Evaluation in the Cloud"
authors:
- Lin Liu
- admin
- Ximeng Liu
- Jinshu Su
- Linbo Qiao

date: "2020-03-11T00:00:00Z"
doi: "10.1109/TIFS.2020.2980192"

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

abstract: "Due to the capacity of storing massive data and
providing huge computing resources, cloud computing has been
a desirable platform for doing machine learning. However, the
issue of data privacy is far from being well solved and thus
has been a general concern in the cloud-aided machine learning.
In this work, we investigate the study of how to efficiently do
decision tree training and evaluation in the cloud and meanwhile
achieve privacy preservation. Unlike existing cloud server-assisted
model training approaches, in our proposed solution, the whole
training process is mostly done by the cloud service provider who
owns the machine learning model. Since the cloud cannot directly
divide the encrypted dataset according to the best attributes
selected, we propose a new method for decision tree training
without dataset splitting. Precisely, we design three methods
for decision tree training with the different tradeoff between
privacy and efficiency. In all of these methods, the outsourced
data are not revealed to the cloud service provider. We also
propose a privacy-preserving decision tree evaluation scheme
where the cloud service provider learns nothing about the user’s
input and the classification result while the trained model is
kept secret to the user who could only learn the classification
result. Compared with previous decision tree evaluation work,
our scheme achieves desirable privacy preservation against both
the user and the cloud service provider, and also minimizes the
user’s computation and communication costs. Moreover, besides
protecting the data confidentiality, our proposed scheme also
supports off-line users and thus has good scalability. The realworld
dataset-based experimental results demonstrate that our
system is of desirable utility and efficiency."

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
  caption: 'Fig.1 **System model**'
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


