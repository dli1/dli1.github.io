---
title: 'Scalable Patent Classification with Aggregated Multi-View Ranking'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Vikrant Yadav
  - Zi Long Zhu
  - Maziar Moradi Fard
  - Zubair Afzal
  - Georgios Tsatsaronis 


# Author notes (optional)
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: "2024-07-17T00:00:00Z"

doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation*
publication_short: In *LREC-COLING '24*
abstract: Automated patent classification typically involves assigning labels to a patent from a taxonomy, using multi-class multi-label classification models. However, classification-based models face challenges in scaling to large numbers of labels, struggle with generalizing to new labels, and fail to effectively utilize the rich information and multiple views of patents and labels. In this work, we propose a multi-view ranking-based method to address these limitations. Our method consists of four ranking-based models that incorporate different views of patents and a meta-model that aggregates and re-ranks the candidate labels given by the four ranking models. We compared our approach against the state-of-the-art baselines on two publicly available patent classification datasets, USPTO-2M and CLEF-IP-2011. We demonstrate that our approach can alleviate the aforementioned limitations and achieve a new state-of-the-art performance by a significant margin.


# Summary. An optional shortened abstract.
summary: We propose a multi-view ranking-based method for patent classification. Our method consists of four ranking-based models that incorporate different views of patents and a meta-model that aggregates and re-ranks the candidate labels given by the four ranking models.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://aclanthology.org/2024.lrec-main.1249/'
url_code: ''
url_dataset: ''
# url_poster: 'https://tba'
url_project: ''
url_slides: 'https://drive.google.com/file/d/1nku2IuII-b6Gn5GPwbten-JVTvi2Eo6Y/view?usp=drive_link'
url_source: ''
url_video: 'https://drive.google.com/file/d/1OnLEqF7woxQv0ZV6jQ-biiQrKWcBfYzi/view?usp=drive_link'

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
<!-- 
{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
