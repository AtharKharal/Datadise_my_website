+++
title = "Comparison of ACO and GA techniques to generate neural network based Bezier-PARSEC parameterized airfoil"
date = "2015-06-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["W Saleem", "Athar Kharal", "R Ahmad", "A Saleem"]

# Publication type.
# Legend: 0 = Uncategorized, 1 = Conference proceedings, 2 = Journal, 3 = Work in progress, 4 = Technical report, 5 = Book, 6 = Book chapter

publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "Natural Computation (ICNC) 11th International Conference on"
publication_short = "In *ICNC 2015*"

# Abstract and optional shortened version.
abstract = "Neural Networks in conjunction with Ant Colony Optimization (ACO), Genetic Algorithms (GAs) have been used to determine two dimensional airfoil geometry using Bezier-PARSEC parameterization."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = ["phds_in_pakistan"]

# Links (optional).
url_pdf = "#"
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
url_custom = [{name = "", url = "#"}]

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

This research uses Neural Networks to determine two dimensional airfoil geometry using Bezier-PARSEC parameterization. Earlier, Ant Colony Optimization (ACO) techniques have 
been used to solve combinatorial optimization problems like TSP. This work extends ACO 
method from TSP problem to design parameters for estimating unknown Bezier-PARSEC 
parameters that define upper and lower curves of the airfoil. The efficiency and the 
performance of ACO technique was compared to that of GA. The work established that ACO 
exhibited improved performance than the GA in terms of optimization time and level of 
precision achieved. In the next phase, Neural Network is implemented using Cp as input in 
terms of Cl, Cd and Cm for learning and targeting the corresponding Bezier-PARSEC 
parameters. Neural Networks including Feed-forward back propagation, Generalized Regression and Radial Basis Neural Networks.
