+++
title = "Overcoming Catastrophic Forgetting by Incremental Moment Matching"

# Date first published.
date = "2017-03-24"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Sang-Woo Lee", "Jin-Hwa Kim", "Jaehyun Jun", "Jung-Woo Ha", "Byoung-Tak Zhang"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In *Advances In Neural Information Processing Systems 30*"
publication_short = "In *NIPS* (Spotlight)"

# Abstract and optional shortened version.
abstract = "Catastrophic forgetting is a problem of neural networks that loses the information of the first task after training the second task. Here, we propose a method, i.e. incremental moment matching (IMM), to resolve this problem. IMM incrementally matches the moment of the posterior distribution of the neural network which is trained on the first and the second task, respectively. To make the search space of posterior parameter smooth, the IMM procedure is complemented by various transfer learning techniques including weight transfer, L2-norm of the old and the new parameter, and a variant of dropout with the old parameter. We analyze our approach on a variety of datasets including the MNIST, CIFAR-10, Caltech-UCSD-Birds, and Lifelog datasets. The experimental results show that IMM achieves state-of-the-art performance by balancing the information between an old and a new network."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Links (optional).
url_pdf = "http://papers.nips.cc/paper/7051-overcoming-catastrophic-forgetting-by-incremental-moment-matching.pdf"
url_preprint = "https://arxiv.org/abs/1703.08475"
url_code = "https://github.com/btjhjeon/IMM_tensorflow"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = "files/imm-nips17-poster v9.pdf"
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "imm.jpg"
caption = ""

+++

NIPS 2017 Spotlight
