+++
title = "Fast path-based timing analysis for CPPR"
date = 2014-11-02

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["T.-W. Huang", "P.-C. Wu", "M. Wong"]

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
publication = "IEEE/ACM International Conference on Computer-Aided Design (ICCAD)"

# Abstract.
abstract = "Common-path-pessimism removal (CPPR) is a pivotal step to achieve accurate timing signoff. Unnecessary pessimism might arise quality-of-result (QoR) concerns such as reporting worse violations than the true timing properties owned by the physical circuit. In other words, signoff timing report will conclude a lower clock frequency at which circuits can operate than actual silicon implementations. Therefore, we introduce in this paper a fast path-based timing analysis for CPPR. Unlike existing approaches which are dominated by explicit path search, we perform implicit path representation which yields significantly smaller search space and faster runtime. Specifically, our algorithm is superior in both space and time saving, from which the memory storage and important timing quantities are available in constant space and constant time per path during the search. Experimental results on industrial benchmarks released from TAU 2014 timing analysis contest have shown that our algorithm won the first place and achieved the best result in terms of accuracy and runtime over all participating teams."

# Summary. An optional shortened abstract.

# Digital Object Identifier (DOI)
doi = "10.1109/ICCAD.2014.7001413"

# Is this a featured publication? (true/false)
featured = false

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["path-based-timing-analysis", "static-timing-analysis", "common-path-pessimism-removal"]

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#projects = ["internal-project"]

# Links (optional).
url_pdf = "iccad14-1.pdf"
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


