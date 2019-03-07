+++
title = "A Contamination Aware Droplet Routing Algorithm for the Synthesis of Digital Microfluidic Biochips"
date = 2010-10-18

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["T.-W. Huang", "C.-H. Lin", "T.-Y. Ho"]

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
abstract = "Recent advances of digital microfluidic biochips (DMFBs) have revolutionized the traditional laboratory procedures. By providing the droplet-based system, DMFB can perform real-time biological analysis and safety-critical biomedical applications. However, different droplets being transported and manipulated on the DMFB may introduce the contamination problem caused by liquid residue between different biomolecules. To overcome this problem, a wash droplet is introduced to clean the contaminations on the surface of the microfluidic array. However, current scheduling of wash droplet does not restrict the extra used cells and execution time of bioassay, thereby degrading the reliability and fault-tolerance significantly. In this paper, we propose a contamination aware droplet routing algorithm for DMFBs. To reduce the routing complexity and the used cells, we first construct preferred routing tracks by analyzing the global moving vector of droplets to guide the droplet routing. To cope with contaminations within one subproblem, we first apply a k -shortest path routing technique to minimize the contaminated spots. Then, to take advantage of multiple wash droplets, we adopt a minimum cost circulation (MCC) algorithm for optimal wash-droplet routing to simultaneously minimize used cells and the cleaning time. Since the droplet routing problem consists of several subproblems, a look-ahead prediction technique is further used to determine the contaminations between successive subproblems. After that, we can simultaneously clean both contaminations within one subproblem and those between successive subproblems by using the MCC-based algorithm to reduce the execution time and the used cells significantly. Based on four widely used bioassays, our algorithm reduces the used cells and the execution time significantly compared with the state-of-the-art algorithm."

# Summary. An optional shortened abstract.
#summary = ""

# Digital Object Identifier (DOI)
doi = "10.1109/TCAD.2010.2062770"

# Is this a featured publication? (true/false)
featured = false

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["digital-microfluidic-biochip", "routing"]

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#projects = ["internal-project"]

# Links (optional).
url_pdf = "tcad10.pdf"
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


