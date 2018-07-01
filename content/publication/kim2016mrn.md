+++
title = "Multimodal Residual Learning for Visual QA"

# Date first published.
date = "2016-06-05"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Jin-Hwa Kim", "Sang-Woo Lee", "Donghyun Kwak", "Min-Oh Heo", "Jeonghee Kim", "Jung-Woo Ha", "Byoung-Tak Zhang"]

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
publication = "In *Advances In Neural Information Processing Systems 29*"
publication_short = "In *NIPS*"

# Abstract and optional shortened version.
abstract = "Deep neural networks continue to advance the state-of-the-art of image recognition tasks with various methods. However, applications of these methods to multimodality remain limited. We present Multimodal Residual Networks (MRN) for the multimodal residual learning of visual question-answering, which extends the idea of the deep residual learning. Unlike the deep residual learning, MRN effectively learns the joint representation from visual and language information. The main idea is to use element-wise multiplication for the joint residual mappings exploiting the residual learning of the attentional models in recent studies. Various alternative models introduced by multimodality are explored based on our study. We achieve the state-of-the-art results on the Visual QA dataset for both Open-Ended and Multiple-Choice tasks. Moreover, we introduce a novel method to visualize the attention effect of the joint representations for each learning block using back-propagation algorithm, even though the visual features are collapsed without spatial information."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Links (optional).
url_pdf = "http://papers.nips.cc/paper/6446-multimodal-residual-learning-for-visual-qa.pdf"
url_preprint = "http://arxiv.org/abs/1606.01455"
url_code = "https://github.com/jnhwkim/nips-mrn-vqa"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = "https://www.youtube.com/watch?v=fsQNAptltn8"
url_poster = "https://bi.snu.ac.kr/~jhkim/posters/mrn-nips16-poster.pdf"
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
image = "https://pbs.twimg.com/media/CkYXU2lW0AAGkND.jpg:large"
caption = "A schematic diagram of MRN"

+++

SotA of non-attention models
