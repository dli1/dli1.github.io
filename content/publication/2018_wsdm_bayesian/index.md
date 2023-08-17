---
title: 'Bayesian optimization for optimizing retrieval systems'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
 - Evangelos Kanoulas


# Author notes (optional)
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: "2018-01-01T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the Eleventh ACM International Conference on Web Search and Data Mining*
publication_short: In *WSDM '18*
abstract: The effectiveness of information retrieval systems heavily depends on a large number of hyperparameters that need to be tuned. Hyperparameters range from the choice of different system components, e.g., stopword lists, stemming methods, or retrieval models, to model parameters, such as k1 and b in BM25, or the number of query expansion terms. Grid and random search, the dominant methods to search for the optimal system configuration, lack a search strategy that can guide them in the hyperparameter space. This makes them inefficient and ineffective. In this paper, we propose to use Bayesian Optimization to jointly search and optimize over the hyperparameter space. Bayesian Optimization, a sequential decision making method, suggests the next most promising configuration to be tested on the basis of the retrieval effectiveness of configurations that have been examined so far. To demonstrate the efficiency and effectiveness of Bayesian Optimization we conduct experiments on TREC collections, and show that Bayesian Optimization outperforms manual tuning, grid search and random search, both in terms of retrieval effectiveness of the configuration found, and in terms of efficiency in finding this configuration.



# Summary. An optional shortened abstract.
# summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/abs/10.1145/3159652.3159665?casa_token=1ELzQN-QZewAAAAA:XBgObjjudViRT-TlCbYi5ckAiEINMjpYTaMscnnJ4cCpM7JYdY3z-_R-es4sJW2boQuaYbTFNMD9ZLs'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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
