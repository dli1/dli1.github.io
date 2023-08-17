---
title: 'Active sampling for large-scale information retrieval evaluation'

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

date: "2017-01-01T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 2017 ACM on Conference on Information and Knowledge Management*
publication_short: In *CIKM '17*
abstract: Evaluation is crucial in Information Retrieval. The development of models, tools and methods has significantly benefited from the availability of reusable test collections formed through a standardized and thoroughly tested methodology, known as the Cranfield paradigm. Constructing these collections requires obtaining relevance judgments for a pool of documents, retrieved by systems participating in an evaluation task; thus involves immense human labor. To alleviate this effort different methods for constructing collections have been proposed in the literature, falling under two broad categories, (a) sampling, and (b) active selection of documents. The former devises a smart sampling strategy by choosing only a subset of documents to be assessed and inferring evaluation measure on the basis of the obtained sample; the sampling distribution is being fixed at the beginning of the process. The latter recognizes that systems contributing documents to be judged vary in quality, and actively selects documents from good systems. The quality of systems is measured every time a new document is being judged. In this paper we seek to solve the problem of large-scale retrieval evaluation combining the two approaches. We devise an active sampling method that avoids the bias of the active selection methods towards good systems, and at the same time reduces the variance of the current sampling approaches by placing a distribution over systems, which varies as judgments become available. We validate the proposed method using TREC data and demonstrate the advantages of this new method compared to past approaches.



# Summary. An optional shortened abstract.
# summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/abs/10.1145/3132847.3133015?casa_token=-r11eTa_gm8AAAAA:AMB9_1Wi26jo_s_V0aOWouC_LQg0ffIHj02zQYY_7XFthd8uy2jc-2q9Nw374cFGTjNnVXWMNhL7i7g'
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
