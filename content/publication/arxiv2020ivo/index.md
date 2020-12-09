+++

title = "IVO: Instance-based Visual Odometry"
date = 2020-11-18T00:00:00
draft = false

# Authors. Comma separated list, e.g. ["Bob Smith", "__**David Jones**__"].
authors = ["Guoxiang Zhou*", "__**Zijian Dong***__", "Zhaopeng Cui", "Marc Pollefeys", "Torsten Sattler"]

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
abstract = "Establishing strong data association and handling dynamicenvironments are two challenges for visual odometry (VO). In this pa-per, we propose a novel instance-based visual odometry to tackle thesechallenges  by  leveraging  both  category-level  and  instance-level  seman-tic information. On one hand, we integrate the instance-level semanticconstraint between map points and camera poses into a general visualodometry framework. In order to establish more constraints for feature-less objects, we propose to generate virtual 3D instance points. We alsomodel the uncertainty of the object tracking to improve the robustnessof the general VO framework. On the other hand, we propose practicaldynamic object detection methods for both monocular and stereo visualodometry based on the instance-level semantic information. Experimentsshow that our method outperforms the state-of-the-art baselines on dif-ferent  benchmark  datasets  and  demonstrate  the  benefit  of  our  generalinstance-based visual odometry. "


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
tags = ["Visual Odometry", "Semantic Segmentation","Instance Segmentation", "Object Tracking"]

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
