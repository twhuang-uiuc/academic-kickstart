+++
title = "UI-Route: An Ultra-Fast Incremental Maze Routing Algorithm"
date = 2014-01-01

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
publication = "ACM/IEEE International Workshop on System Level Interconnect Prediction (SLIP)"

# Abstract.
abstract = "Grid-based maze routing is a fundamental problem in electronic-design-automation (EDA) domain. A core primitive deals with a large query set about route connectivity subject to incremental changes on grid graph. Existing approaches pertain to batch processing, where each route query is independently and repeatedly solved by a routing procedure. Few researches so far discuss an efficient utilization of search knowledge in incremental fashion, which could dramatically speed up the search. Unfortunately, existing algorithms nearly rely on irregular and highly divergent search space, imposing acceleration challenges on refitting them to incremental version. Consequently, in this paper we present UI-Route, an ultra-fast incremental maze routing algorithm in grid environment. UI-Route is unique in breaking route equivalence, proving that a huge amount of equivalent search efforts can be optimally and incrementally eliminated. Equivalence breaking enables regularized search space, delivering well-tabulated search knowledge through the incremental processing. Moreover UI-Route is largely orthogonal to many applications built upon maze routing and therefore can seamlessly substitute for speedup. Experimental results on a set of modern circuit benchmarks demonstrate that UI-Route achieves prominent speedup over existing algorithms."

# Summary. An optional shortened abstract.

# Digital Object Identifier (DOI)
doi = "10.1145/2633948.2633952"

# Is this a featured publication? (true/false)
featured = false

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["routing"]

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#projects = ["internal-project"]

# Links (optional).
url_pdf = "slip14.pdf"
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


