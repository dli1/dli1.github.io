---
title: 'Query resolution for conversational search with limited supervision'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Nikos Voskarides
  - admin
  - Pengjie Ren
  - Maarten de Rijke

# Author notes (optional)
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: "2020-01-01T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 43rd International ACM SIGIR Conference on Research and Development in Information Retrieval*
publication_short: In *SIGIR '20*
abstract: In this work we focus on multi-turn passage retrieval as a crucial component of conversational search. One of the key challenges in multi-turn passage retrieval comes from the fact that the current turn query is often underspecified due to zero anaphora, topic change, or topic return. Context from the conversational history can be used to arrive at a better expression of the current turn query, defined as the task of query resolution. In this paper, we model the query resolution task as a binary term classification problem, for each term appearing in the previous turns of the conversation decide whether to add it to the current turn query or not. We propose QuReTeC (Query Resolution by Term Classification), a neural query resolution model based on bidirectional transformers. We propose a distant supervision method to automatically generate training data by using query-passage relevance labels. Such labels are often readily available in a collection either as human annotations or inferred from user interactions. We show that QuReTeC outperforms state-of-the-art models, and furthermore, that our distant supervision method can be used to substantially reduce the amount of human-curated data required to train QuReTeC. We incorporate QuReTeC in a multi-turn, multi-stage passage retrieval architecture and demonstrate its effectiveness on the TREC CAsT dataset.



# Summary. An optional shortened abstract.
# summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/abs/10.1145/3397271.3401130?casa_token=xPOb0Ip17EkAAAAA:IVU1kUddEH1jZX4M-WA9MnImjYlSEcXVJxkl8-TAg98hg8hcSX2BWgPrKcYK7eEGTxXe0cDyJpp_V5I'
url_code: 'https://github.com/nickvosk/sigir2020-query-resolution'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://dl.acm.org/doi/10.1145/3397271.3401130'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ''
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: content/slides/example/index.md

---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
