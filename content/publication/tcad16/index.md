+++
title = "UI-Timer 1.0: An Ultrafast Path-Based Timing Analysis Algorithm for CPPR"
date = 2016-02-08

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
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "IEEE IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD)"
#publication_short = "IEEE TCAD"

# Abstract.
abstract = "The recent TAU computer-aided design (CAD) contest has aimed to seek novel ideas for accurate and fast common path pessimism removal (CPPR). Unnecessary pessimism forces the static timing analysis tool to report worse violation than the true timing properties owned by physical circuits, thereby misleading signoff timing into a lower clock frequency at which circuits can operate than actual silicon implementations. Therefore, we introduce in this paper UI-Timer 1.0, a powerful CPPR algorithm which achieves high accuracy and ultrafast runtime. Unlike existing approaches which are dominated by explicit path search, UI-Timer 1.0 proves that by implicit path representation the amount of search effort can be significantly reduced. Our timer is superior in both space and time saving, from which memory storage and important timing quantities are available in constant space and constant time per path during the search. Experimental results on industrial benchmarks released from TAU 2014 CAD contest have justified that UI-Timer 1.0 achieved the best result in terms of accuracy and runtime over existing CPPR algorithms."

# Summary. An optional shortened abstract.
#summary = ""

# Digital Object Identifier (DOI)
doi = "10.1109/TCAD.2016.2524566"

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
url_pdf = "tcad16.pdf"
#url_preprint = ""
url_code = "https://github.com/OpenTimer"
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


