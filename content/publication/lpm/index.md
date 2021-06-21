---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Localized Pattern Mining"
authors: ["Amir Dib*, Cyrus Cousins*"]
date: 2021-06-01T16:26:14+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-06-21T16:26:14+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Conference on Neural Information Processing Systems (NeurIPS 2020), Vancouver, Canada."
publication_short: "NeurIPS2020"

abstract: "This paper considers the problem of finding the best sampling strategy for pattern mining problems, which can be stated as the task of computing the frequency at which a pattern, or a set of events, occurs in a database.
This problem is ubiquitous in data mining, and is typically intractable, due to the exponentially large number of possible patterns that must be evaluated.
Recent approaches use traditional tools from statistical learning theory to obtain uniform additive bounds on these frequencies, which are effective for \emph{frequent patterns}, but are generally unsatisfying for \emph{infrequent patterns}, which are typically the hardest to mine exactly.
In this work, we propose the first bound based on \emph{localized Rademacher averages} (LRAs) in the context of pattern mining.
We show that localized Rademacher averages are sufficient to obtain relative confidence interval estimates on pattern frequencies, as well as other interestingness measures, such as the \emph{lift}, \emph{confidence}, or \emph{odds ratio}, whereas previous message fail to do so for low-frequency patterns.
Our methods rely on standard tools in the pattern mining repertoire, such as closed pattern families, antimonotonicity, and Monte-Carlo Rademacher averages, as well as new techniques we introduce to address the problem-specific computational challenges arising from evaluating the localized Rademacher average.
The performance of our approach is empirically demonstrated on real-world datasets, wherein exhibit fast convergence rates for the considered subclass of patterns, sharply contrasting existing work."
# Summary. An optional shortened abstract.
summary: "Submitted."

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
