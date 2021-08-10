+++

title = "Shape-aware Multi-Person Pose Estimation from Multi-View Images"
date = 2021-08-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. ["Bob Smith", "__**David Jones**__"].
authors = ["Zijian Dong", "Jie Song", "Xu Chen", "Chen Guo", "Otmar Hilliges"]

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
publication_short = "*ICCV'2021*"

# Abstract and optional shortened version.
abstract = "In this  paper  we  contribute  a  simple  yet  effective  ap-proach  for  estimating  3D  poses  of  multiple  people  frommulti-view  images.   Our  proposed  coarse-to-fine  pipelinefirst aggregates noisy 2D observations from multiple cam-era views into 3D space and then associates them into indi-vidual instances based on a confidence-aware majority vot-ing technique.  The final pose estimates are attained froma  novel  optimization  scheme  which  links  high-confidencemulti-view 2D observations and 3D joint candidates. More-over, a statistical parametric body model such as SMPL isleveraged as a regularizing prior for these 3D joint candi-dates.   Specifically,  both 3D poses and SMPL parametersare  optimized  jointly  in  an  alternating  fashion.   Here  theparametric models help in correcting implausible 3D poseestimates and filling in missing joint detections while up-dated 3D poses in turn guide obtaining better SMPL esti-mations.  By linking 2D and 3D observations, our methodis both accurate and generalizes to different data sourcesbecause it better decouples the final 3D pose from the inter-person  constellation  and  is  more  robust  to  noisy  2D  de-tections.  We systematically evaluate our method on publicdatasets and achieve state-of-the-art performance."
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
tags = ["human pose"]

# Links (optional).
#url_pdf = "https://arxiv.org/abs/2008.08145"
#url_code = "https://github.com/guochengqian/TENet"
#url_dataset = "project/pixelshift200"
#url_slides = "https://docs.google.com/presentation/d/1L82wWymMnHyYJk3xUKvteEWD5fX0jVRbCbI65Cxxku0/edit?usp=sharing"
#url_video = "https://youtu.be/CHB96wBV4Ts"
#url_poster = ""
#url_project = "https://ait.ethz.ch/projects/2020/neural-object-fitting/"

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
