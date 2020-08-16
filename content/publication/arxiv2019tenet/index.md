+++

title = "Trinity of Pixel Enhancement: a Joint Solution for Demosaicking, Denoising and Super-Resolution"
date = 2019-05-07T00:00:00
draft = false

# Authors. Comma separated list, e.g. ["Bob Smith", "__**David Jones**__"].
authors = ["__**Guocheng Qian***__", "Jinjin Gu*", "Jimmy S. Ren", "Chao Dong", "Furong Zhao", "Juan Lin"]

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
publication_short = "*arXiv'2019*"

# Abstract and optional shortened version.
abstract = "Demosaicing, denoising and super-resolution (SR) are of practical importance in digital image processing and have been studied independently in the passed decades. Despite the recent improvement of learning-based image processing methods in image quality, there lacks enough analysis into their interactions and characteristics under a realistic setting of the mixture problem of demosaicing, denoising and SR. In existing solutions, these tasks are simply combined to obtain a high-resolution image from a low-resolution raw mosaic image, resulting in a performance drop of the final image quality. In this paper, we first rethink the mixture problem from a holistic perspective and then propose the Trinity Enhancement Network (TENet), a specially designed learning-based method for the mixture problem, which adopts a novel image processing pipeline order and a joint learning strategy. In order to obtain the correct color sampling for training, we also contribute a new dataset namely PixelShift200, which consists of high-quality full color sampled real-world images using the advanced pixel shift technique. Experiments demonstrate that our TENet is superior to existing solutions in both quantitative and qualitative perspective. Our experiments also show the necessity of the proposed PixelShift200 dataset."
# abstract_short = "Demosaicing, denoising and super-resolution (SR) are of practical importance in digital image processing and have been studied independently in the passed decades. Despite the recent improvement of learning-based image processing methods in image quality, there lacks enough analysis into their interactions and characteristics under a realistic setting of the mixture problem of demosaicing, denoising and SR ...(View more by click the title)"


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
projects = ["pixelshift200"]

# Slides (optional).
# Associate this publication with Markdown slides.
# Simply enter your slide deck's filename without extension.
# E.g. slides = "example-slides" references
# content/slides/example-slides.md.
# Otherwise, set slides = "".
slides = ""

# Tags (optional).
# Set tags = [] for no tags, or use the form tags = ["A Tag", "Another Tag"] for one or more tags.
tags = ["super-resolution", "image processing"]

# Links (optional).
url_preprint = "https://arxiv.org/abs/1905.02538"
url_code = "https://github.com/guochengqian/TENet"
url_dataset = "project/pixelshift200"
#url_slides = "https://docs.google.com/presentation/d/1L82wWymMnHyYJk3xUKvteEWD5fX0jVRbCbI65Cxxku0/edit?usp=sharing"
#url_video = "https://youtu.be/CHB96wBV4Ts"
#url_poster = ""
#url_source = ""

# Custom links (optional).
# Uncomment line below to enable. For multiple links, use the form [{...}, {...}, {...}].
# url_custom = [{name = "Custom Link", url = "http://example.org"}]
# Digital Object Identifier (DOI)
doi = ""

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
