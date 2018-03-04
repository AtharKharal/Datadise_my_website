+++
title = "Neural Networks Based Airfoil Generation for a Given Cp Using Bezier-PARSEC Parameterization"
date = "2012-06-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Athar Kharal", "Aymen Saleem"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "*Aerospace Science and Technology*"
publication_short = "In *AST*, Elsevier"

# Abstract and optional shortened version.
abstract = "This is one my major result of the work we have been doing since many years. Applying Neural Networks and Genetic Algorithms based machine-learning and optimization on a variety of problems in the field of Aerospace Engineering we transformed the slow computation into lightening-fast tools based upon neural computation based machine learning."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = ["ann_and_GAs_for_airfoil_geos_aymen"]

# Links (optional).
url_pdf = "https://www.sciencedirect.com/science/article/pii/S1270963811001398"
url_preprint = "#"
url_code = "#"
url_dataset = "#"
url_project = "#"
url_slides = "#"
url_video = "#"
url_poster = "#"
url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{name = "ScienceDirect", url = "https://www.sciencedirect.com/science/article/pii/S1270963811001398"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "headers/bubbles-wide.jpg"
caption = "Athar Kharal and Aymen Saleem"

+++
Determining the airfoil geometry from a given C p-distribution is an inverse problem of paramount importance specially in the context of variable geometry aerodynamic platforms. This work describes the implementation of artificial neural nets for the airfoil geometry determination. Instead of using full coordinates of the airfoil, Bezier-PARSEC 3434 parameters have been used to describe an airfoil. Some of these parameters have been determined using a Genetic Algorithm. In the second stage C p-distribution in terms of cl, cd and cm for 10 angles of attack has been input into three different neural nets for learning and then estimating the corresponding BP3434 parameters. Feed-forward backpropagation, Generalized regression and Radial basis neural nets have been trained and then compared in terms of performance and regression statistics.
 
