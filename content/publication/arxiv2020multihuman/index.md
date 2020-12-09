+++

title = "Shape-aware Multi-Person Pose Estimation from Multi-View Images"
date = 2020-11-18T00:00:00
draft = false

# Authors. Comma separated list, e.g. ["Bob Smith", "__**David Jones**__"].
authors = ["__**Zijian Dong**__", "Jie Song", "Xu Chen", "Chen Guo", "Otmar Hilliges"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["0"]

# Publication name and optional abbreviated version.
publication =""
publication_short = "submitted to CVPR2021"

# Abstract and optional shortened version.
abstract = "In this paper we contribute a coarse-to-fine approachfor estimating 3D poses of multiple people from multi-viewimages. In contrast to state-of-the-art methods that lever-age latent volumetric 3D representations to directly regresspose parameters, we formulate the task as a novel optimiza-tion problem that links high-confidence 2D observationsand 3D joint location candidates via a statistical parameteric body model such as SMPL, used as regularizing prior. Specifically, we propose an energy formulation in which both a multi-view re-projection error and a 3D body modelfitting term are optimized in an alternating fashion. Herethe 3D body model helps in correcting unrealistic pose estimates and in filling in missing joint detections. Thus bylinking 2D and 3D observations our method is both accu-rate and generalizes to different data sources because it bet-ter decouples the final 3D pose from the inter-person constellation and is more robust to noisy 2D detections. We systematically evaluate our method on public datasets andachieve state-of-the-art performance."


# Is this a selected publication? (true/false)
selected = true
# Is this a featured publication? (true/false)
featured = true

# Projects (optional).
# Associate this publication with one or more of your projects.
# Simply enter your project's folder or file name without extension.
# E.g. projects = ["deep-learning"] references
# content/project/deep-learning/index.md.
# Otherwise, set projects = [].
projects = []

# Slides (optional).
# Associate this publication with Markdown slides.
# Simply enter your slide deck's filename without extension.
# E.g. slides = "example-slides" references
# content/slides/example-slides.md.
# Otherwise, set slides = "".
slides = ""

# Tags (optional).
# Set tags = [] for no tags, or use the form tags = ["A Tag", "Another Tag"] for one or more tags.
tags = ["3D human pose"]

# Links (optional).
#url_preprint = "https://arxiv.org/abs/1912.03264.pdf"
#url_code = "https://github.com/guochengqian/PU-GCN"
#url_video = "https://www.youtube.com/watch?v=dbWLdnq0FQ8"
#url_project = "https://sites.google.com/kaust.edu.sa/pugcn"
#url_dataset = "https://sites.google.com/kaust.edu.sa/pugcn"
#url_abstract = "Upsampling sparse, noisy, and non-uniform point clouds is a challenging task. In 
# Custom links (optional).
# Uncomment line below to enable. For multiple links, use the form [{...}, {...}, {...}].
#url_website =  [{name = "website", url = "https://sites.google.com/kaust.edu.sa/pugcn"}]
# Digital Object Identifier (DOI)


# Does this page contain LaTeX math? (true/false)
math = false

# To use, place an image named `featured.jpg/png` in your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
# Set `preview_only` to `true` to just use the image for thumbnails.

[image]  
  # Caption (optional)
  # caption = "123"
  
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Center"
  placement = 2
  # preview_only = true

+++
