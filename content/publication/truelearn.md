+++
title = "TrueLearn: A Family of Bayesian Algorithms to Match Lifelong Learners to Open Educational Resources"
date = "2020-02-12"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.

authors = ["**Sahan Bulathwela**", "Maria Perez-Ortiz", "Emine Yilmaz", "John Shawe-Taylor"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "AAAI Conference on Artificial Intelligence"
publication_short = "AAAI"

# Abstract and optional shortened version.

abstract = "The recent advances in computer-assisted learning systems and the availability of open educational resources today promise a pathway to providing cost-efficient, high-quality education to large masses of learners. One of the most ambitious use cases of computer-assisted learning is to build a lifelong learning recommendation system. Unlike short-term courses, lifelong learning presents unique challenges, requiring sophisticated recommendation models that account for a wide range of factors such as background knowledge of learners or novelty of the material while effectively maintaining knowledge states of masses of learners for significantly longer periods of time (ideally, a lifetime). This work presents the foundations towards building a dynamic, scalable and transparent recommendation system for education, modelling learner's knowledge from implicit data in the form of engagement with open educational resources. We i) use a text ontology based on Wikipedia to automatically extract knowledge components of educational resources and, ii) propose a set of online Bayesian strategies inspired by the well-known areas of item response theory and knowledge tracing. Our proposal, TrueLearn, focuses on recommendations for which the learner has enough background knowledge (so they are able to understand and learn from the material), and the material has enough novelty that would help the learner improve their knowledge about the subject and keep them engaged. We further construct a large open educational video lectures dataset and test the performance of the proposed algorithms, which show clear promise towards building an effective educational recommendation system."

# Featured image thumbnail (optional)
#image_preview = "static/img/ftl.png"

# Is this a featured publication? (true/false)
featured = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]

# Links (optional).
url_pdf = ""
url_preprint = "https://arxiv.org/abs/1911.09471"
url_code = ""
url_dataset = ""
url_project = "https://www.x5gon.org/"
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#[[url_custom]]
name = "Conference"
#url = "https://aaai.org/Conferences/AAAI-20/"

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true
  
# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
# image = "ftl.png"
#caption = "My caption :smile:"

+++
The first paper outlining the foundations of the TrueLearn Bayesian learner model that recovers the learner's latent knowledge state based on how they engage with videolectures.
In *Proceeding of*, 2020. 
