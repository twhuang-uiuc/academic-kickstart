+++
title = "On fast timing closure: speeding up incremental path-based timing analysis with mapreduce"
date = 2015-06-06

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
publication = "ACM/IEEE International Workshop on System Level Interconnect Prediction (SLIP)"
#publication_short = "IEEE/ACM SLIP"

# Abstract.
abstract = "Incremental path-based timing analysis (PBA) is a pivotal step in the timing optimization flow. A core building block analyzes the timing path-by-path subject to a critical amount of incremental changes on the design. However, this process in nature demands an extremely high computational complexity and has been a major bottleneck in accelerating timing closure. Therefore, we introduce in this paper a fast and scalable algorithm of incremental PBA with MapReduce - a recently popular programming paradigm in big-data era. Inspired by the spirit of MapReduce, we formulate our problem into tasks that are associated with keys and values and perform massively-parallel map and reduce operations on a distributed system. Experimental results demonstrated that our approach can not only easily analyze huge deisgns in a few minutes, but also quickly revalidate the timing after the incremental changes. Our results are beneficial for speeding up the lengthy design cycle of timing closure."

# Summary. An optional shortened abstract.

# Digital Object Identifier (DOI)
doi = "10.1109/SLIP.2015.7171710"

# Is this a featured publication? (true/false)
featured = false

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["path-based-timing-analysis", "static-timing-analysis"]

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#projects = ["internal-project"]

# Links (optional).
#url_pdf = ""
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


