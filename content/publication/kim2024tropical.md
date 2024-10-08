+++
title = "Polyhedral Complex Derivation from Piecewise Trilinear Networks"

# Date first published.
date = "2024-12-09"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Jin-Hwa Kim"]

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
publication = "In *Advances in Neural Information Processing Systems 37*"
publication_short = "In *NeurIPS*"

# Abstract and optional shortened version.
abstract = "Recent advancements in visualizing deep neural networks provide insights into their structures and mesh extraction from Continuous Piecewise Affine (CPWA) functions. Meanwhile, developments in neural surface representation learning incorporate non-linear positional encoding, addressing issues like spectral bias; however, this poses challenges in applying mesh extraction techniques based on CPWA functions. Focusing on trilinear interpolating methods as positional encoding, we present theoretical insights and an analytical mesh extraction, showing the transformation of hypersurfaces to flat planes within the trilinear region under the eikonal constraint. Moreover, we introduce a method for approximating intersecting points among three hypersurfaces contributing to broader applications. We empirically validate correctness and parsimony through chamfer distance and efficiency, and angular distance, while examining the correlation between the eikonal loss and the planarity of the hypersurfaces."
abstract_short = "Recent advancements in deep neural network visualization reveal insights into mesh extraction from Continuous Piecewise Affine (CPWA) functions, while neural surface representation learning addresses spectral bias but complicates CPWA-based techniques. We focus on trilinear interpolation as positional encoding, showing how hypersurfaces transform into flat planes under the eikonal constraint and introducing a method for approximating intersection points among three hypersurfaces. Empirical validation confirms the correctness and efficiency of our approach through chamfer and angular distance, highlighting the link between eikonal loss and hypersurface planarity."

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
url_pdf = ""
url_preprint = "https://arxiv.org/abs/2402.10403"
url_code = "https://github.com/naver-ai/tropical-nerf.pytorch"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
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
image = "kim2024tropical_overview.png"
caption = ""

+++
