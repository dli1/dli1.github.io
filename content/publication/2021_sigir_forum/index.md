---
title: 'Effective collection construction for information retrieval evaluation and optimization'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin

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
publication: PhD dissertation
publication_short: PhD dissertation
abstract: The availability of test collections in Cranfield paradigm has significantly benefited the development of models, methods and tools in information retrieval. Such test collections typically consist of a set of topics, a document collection and a set of relevance assessments. Constructing these test collections requires effort of various perspectives such as topic selection, document selection, relevance assessment, and relevance label aggregation etc. The work in the thesis provides a fundamental way of constructing and utilizing test collections in information retrieval in an effective, efficient and reliable manner. To that end, we have focused on four aspects. \n We first study the document selection issue when building test collections. We devise an active sampling method for efficient large-scale evaluation [Li and Kanoulas, 2017]. Different from past sampling-based approaches, we account for the fact that some systems are of higher quality than others, and we design the sampling distribution to over-sample documents from these systems. At the same time, the estimated evaluation measures are unbiased, and assessments can be used to evaluate new, novel systems without introducing any systematic error. \n Then a natural further step is determining when to stop the document selection and assessment procedure. This is an important but understudied problem in the construction of test collections. We consider both the gain of identifying relevant documents and the cost of assessing documents as the optimization goals. We handle the problem under the continuous active learning framework by jointly training a ranking model to rank documents, and estimating the total number of relevant documents in the collection using a "greedy" sampling method [Li and Kanoulas, 2020]. \n The next stage of constructing a test collection is assessing relevance. We study how to denoise relevance assessments by aggregating from multiple crowd annotation sources to obtain high-quality relevance assessments. This helps to boost the quality of relevance assessments acquired in a crowdsourcing manner. We assume a Gaussian process prior on query-document pairs to model their correlation. The proposed model shows good performance in terms of interring true relevance labels. Besides, it allows predicting relevance labels for new tasks that has no crowd annotations, which is a new functionality of CrowdGP. Ablation studies demonstrate that the effectiveness is attributed to the modelling of task correlation based on the axillary information of tasks and the prior relevance information of documents to queries. \n After a test collection is constructed, it can be used to either evaluate retrieval systems or train a ranking model. We propose to use it to optimize the configuration of retrieval systems. We use Bayesian optimization approach to model the effect of a δ-step in the configuration space to the effectiveness of the retrieval system, by suggesting to use different similarity functions (covariance functions) for continuous and categorical values, and examine their ability to effectively and efficiently guide the search in the configuration space [Li and Kanoulas, 2018]. \n Beyond the algorithmic and empirical contributions, work done as part of this thesis also contributed to the research community as the CLEF Technology Assisted Reviews in Empirical Medicine Tracks in 2017, 2018, and 2019 [Kanoulas et al., 2017, 2018, 2019]. \n Awarded by University of Amsterdam, Amsterdam, The Netherlands. Supervised by Evangelos Kanoulas. Available at https://dare.uva.nl/search?identifier=3438a2b6-9271-4f2c-add5-3c811cc48d42.



# Summary. An optional shortened abstract.
# summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dare.uva.nl/search?identifier=3438a2b6-9271-4f2c-add5-3c811cc48d42'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://dl.acm.org/doi/10.1145/3483382.3483401'
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
