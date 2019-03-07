+++
title = "MtDetector: A High-performance Marine Traffic Detector at Stream Scale"
date = 2018-06-25

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["T.-W. Huang", "C.-X. Lin", "G. Guo", "M. Wong"]

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
publication = "ACM International Conference on Distributed and Event-based Systems (DEBS)"

# Abstract.
abstract = "In this paper, we present MtDetector, a high performance marine traffic detector that can predict the destination and the arrival time of travelling vessels. MtDetector accepts streaming data reported by the moving vessels and generates continuous predictions of the arrival port and arrival time for those vessels. To predict the destination for a ship, MtDetector builds a neural network for every port and infers the arrival port for vessels based on their departure port. For the arrival time prediction, we derive informative features from training data and apply Deep Neural Network (DNN) to estimate the traveling time. MtDetector is built on top of DtCraft, a high-performance distributed execution engine for stream programming. By utilizing the task-based parallelism in DtCraft, MtDetector can process multiple predictions concurrently to achieve high throughput and low latency."

# Digital Object Identifier (DOI)
doi = "10.1145/3210284.3220504"

# Is this a featured publication? (true/false)
featured = false

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["distributed-programming", "machine-learning"]

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#projects = ["internal-project"]

# Links (optional).
url_pdf = "debs18.pdf"
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


