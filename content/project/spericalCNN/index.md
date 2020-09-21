+++

title = "MVPDesc: Multi-View-Point DescriptorLearning for Registration of 3D Objects"
date = 2019-08-07T00:00:00
draft = false

# Authors. Comma separated list, e.g. ["Bob Smith", "__**David Jones**__"].
authors = ["__**Zijian Dong**__", "Johannes L. Schonberger", "Christoph Vogel", "Marc Pollefeys"]

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
publication_short = "*Semester Thesis*"

# Abstract and optional shortened version.
abstract = "Significant to the matching of 3D objects is how to establish correspondences between 3D key-points based on their 3D local descriptors extracted from various 3D representations. Among them,point clouds and multi-view images are easy to obtain and show better performance comparing toothers.  However, little effort focuses on exploring the complementary relationship between them.In this thesis, we investigate the spherical feature map for fusing 2D and 3D data and propose twoapproaches to deal with this problem.  The first approach associates a sphere to a 3D point andprojects it onto the multi-view images that observe the 3D point.  These spheres are combined byweights given the angle between the viewing ray and the normal on the sphere.  However, it failsin experiments due to not using the true geometry of point clouds for projection. Later MVPDescis proposed, which can jointly fuse features from point cloud data and multi-view data.  In thisapproach, the dominant vector of point clouds is first extracted by PCA to guide the stereographicprojection.  This dominant direction defines a projected plane that replaces the sphere as a proxyto combine the information of different views.  For each Delaunay triangular region on projectedplanes, the color information is obtained via projection of original 3D points.  After synthesizingeach projected view and projecting it back to the sphere, the constructed sphere can be further pro-cessed by Spherical CNN to extract descriptors.  To learn descriptors effectively, a triplet networkwith batch hard mining and soft margin loss is built to ensure fast convergence of the algorithm.Experiments show that our MVPDesc achieves robust matching performance and rotation-invariantproperty, which can be further applied to registration of rotated 3D structures."
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
projects = ["computer-vision"]

# Slides (optional).
# Associate this publication with Markdown slides.
# Simply enter your slide deck's filename without extension.
# E.g. slides = "example-slides" references
# content/slides/example-slides.md.
# Otherwise, set slides = "".
slides = ""

# Tags (optional).
# Set tags = [] for no tags, or use the form tags = ["A Tag", "Another Tag"] for one or more tags.
tags = ["3D Matching", "Descriptor Learning"]

# Links (optional).
url_pdf = "project/sphericalCNN/sphericalCNN.pdf"
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
