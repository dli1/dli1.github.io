---
title: 'CrowdGP: A Gaussian Process Model for Inferring Relevance from Crowd Annotations'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Maarten de Rijke

# Author notes (optional)
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: "2021-01-01T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the Web Conference 2021*
publication_short: In *WWW '21*
abstract: Test collection has been a crucial factor for developing information retrieval systems. Constructing a test collection requires annotators to assess the relevance of massive query-document pairs. Relevance annotations acquired through crowdsourcing platforms alleviate the enormous cost of this process but they are often noisy. Existing models to denoise crowd annotations mostly assume that annotations are generated independently, based on which a probabilistic graphical model is designed to model the annotation generation process. However, tasks are often correlated with each other in reality. It is an understudied problem whether and how task correlation helps in denoising crowd annotations. In this paper, we relax the independence assumption to model task correlation in terms of relevance. We propose a new crowd annotation generation model named CrowdGP, where true relevance labels, annotator competence, annotator’s bias towards relevancy, task difficulty, and task’s bias towards relevancy are modelled through a Gaussian process and multiple Gaussian variables respectively. The CrowdGP model shows better performance in terms of interring true relevance labels compared with state-of-the-art baselines on two crowdsourcing datasets on relevance. The experiments also demonstrate its effectiveness in terms of selecting new tasks for future crowd annotation, which is a new functionality of CrowdGP. Ablation studies indicate that the effectiveness is attributed to the modelling of task correlation based on the auxiliary information of tasks and the prior relevance information of documents to queries.



# Summary. An optional shortened abstract.
# summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/abs/10.1145/3442381.3450047?casa_token=HbgLpHqlVIQAAAAA:g1_ZjcPq9IJBOhZ0Qn-L2hmJCvhM4rQcVssV0KHq0JBgi3K-cnkIXFgzCsyo8P8hOzTlAXsJuw2CTT8'
url_code: 'https://github.com/dli1/magp'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://drive.google.com/file/d/1F8Ee9PIglG9oYjVorPBQYrgUfCnaW7BH/view?usp=drive_link'
url_source: ''
url_video: 'https://drive.google.com/file/d/14HAg_YkjnXLIxJVMYeaEVfJVpr9Z6JgR/view?usp=drive_link'

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
