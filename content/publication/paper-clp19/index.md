---
title: "Suicide Risk Assessment with Multi-level Dual-Context Language and BERT"
authors:
- Matthew Matero
- Akash Idnani
- Youngseo Son
- Salvatore Giorgi
- admin
- Mohammad Zamani
- Parth Limbachiya
- Sharath Chandra Guntuku
- H. Andrew Schwartz
date: "2019-06-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Proceedings of the Sixth Workshop on Computational Linguistics and Clinical Psychology  (CLPsych) 2019
publication_short: In *CLPsych19*

abstract: Mental health predictive systems typically model language as if from a single context (e.g. Twitter posts, status updates, or forum posts) and often limited to a single level of analysis (e.g. either the message-level or user-level). Here, we bring these pieces together to explore the use of open-vocabulary (BERT embeddings, topics) and theoretical features (emotional expression lexica, personality) for the task of suicide risk assessment on support forums (the CLPsych-2019 Shared Task). We used dual context based approaches (modeling content from suicide forums separate from other content), built over both traditional ML models as well as a novel dual RNN architecture with user-factor adaptation. We find that while affect from the suicide context distinguishes with no-risk from those with {"}any-risk{"}, personality factors from the non-suicide contexts provide distinction of the levels of risk low, medium, and high risk. Within the shared task, our dual-context approach (listed as SBU-HLAB in the official results) achieved state-of-the-art performance predicting suicide risk using a combination of suicide-context and non-suicide posts (Task B), achieving an F1 score of 0.50 over hidden test set labels.

# Summary. An optional shortened abstract.
summary:

tags:
featured: true

links:
url_pdf: https://www.aclweb.org/anthology/W19-3005/
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# : example
---
