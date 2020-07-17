+++
title = "lorenzgini: generalized Gini for sparse data situations"
date = "2018-03-23"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Wouter Steenbeek", "Wim Bernasco"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
# 7 = Software
publication_types = ["7"]

# Publication name and optional abbreviated version.
publication = ""
publication_short = ""

# Abstract and optional shortened version.
abstract = "[lorenzgini](https://github.com/wsteenbeek/lorenzgini) is an R package that calculcates the standard Gini coefficient as well as the generalized coefficient, and plots Lorenz curves. The Lorenz plots show the line of maximal equality given the data.<br><br>The package builds on [this paper](https://doi.org/10.1007/s10940-016-9324-7) in which Wim Bernasco and I wrote that the crime and place literature lacks a standard methodology for measuring and reporting crime concentration. We suggested that crime concentration be reported with the Lorenz curve and summarized with the Gini coefficient, and we proposed generalized versions of the Lorenz curve and the Gini coefficient to correct for bias when crime data are sparse (i.e., fewer crimes than places).<br><br>The proposed generalizations are based on the principle that the observed crime concentration should not be compared with perfect equality, but with maximal equality given the data. The generalizations asymptotically approach the original Lorenz curve and the original Gini coefficient as the number of crimes approaches the number of spatial units.<br><br>"

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
# projects = ["example-external-project"]

# Links (optional).
url_pdf = ""
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{name = "Package on Github", url = "https://github.com/wsteenbeek/lorenzgini"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++

The most recent version of the package is:

> Steenbeek, W., Bernasco, W. (2018). *`lorenzgini`: generalized Gini for sparse data situations*. R package version 0.1.1. URL: <https://github.com/wsteenbeek/lorenzgini>

To install the package, follow the instructions on its [GitHub repository](https://github.com/wsteenbeek/lorenzgini).