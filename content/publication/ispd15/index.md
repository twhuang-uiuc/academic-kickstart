+++
title = "Accelerated Path-Based Timing Analysis with MapReduce"
date = 2015-03-29

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["T.-W. Huang", "M. Wong"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "ACM Symposium on International Symposium on Physical Design (ISPD)"
#publication_short = "ACM ISPD"

# Abstract.
abstract = "Path-based timing analysis (PBA) is a pivotal step to achieve accurate timing signoff. A core primitive extracts a large set of paths subject to path-specific or less-pessimistic timing update. However, this process in nature demands a very high computational complexity and thus has been a major bottleneck in accelerating timing closure. Therefore, we introduce in this paper a fast and scalable PBA framework with MapReduce - a recent programming paradigm invented by Google for big-data processing. Inspired by the spirit of MapReduce, we formulate our problem into tasks that are associated with keys and values and perform massively-parallel map and reduce operations on a distributed system. Experimental results demonstrated that our approach can easily analyze million nodes in a single minute."

# Summary. An optional shortened abstract.

# Digital Object Identifier (DOI)
doi = "10.1145/2717764.2717771"

# Is this a featured publication? (true/false)
featured = false

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["path-based-timing-analysis", "static-timing-analysis", "distributed-computing", "map-reduce"]

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#projects = ["internal-project"]

# Links (optional).
url_pdf = "ispd15.pdf"
#url_preprint = ""
#url_code = ""
#url_dataset = "#"
#url_project = ""
#url_slides = "#"
#url_video = "#"
#url_poster = "#"
#url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#links = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
#math = false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++


