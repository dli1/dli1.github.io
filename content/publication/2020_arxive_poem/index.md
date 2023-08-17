---
title: 'Paint4Poem: A dataset for artistic visualization of classical Chinese poems'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Shuai Wang
- Jie Zou
- Chang Tian
- Elisha Nieuwburg
- Fengyuan Sun
- Evangelos Kanoulas


# Author notes (optional)
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: "2021-01-01T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication_short: In *Arxiv*
abstract: In this work we propose a new task, artistic visualization of classical Chinese poems, where the goal is to generatepaintings of a certain artistic style for classical Chinese poems. For this purpose, we construct a new dataset called Paint4Poem. Thefirst part of Paint4Poem consists of 301 high-quality poem-painting pairs collected manually from an influential modern Chinese artistFeng Zikai. As its small scale poses challenges for effectively training poem-to-painting generation models, we introduce the secondpart of Paint4Poem, which consists of 3,648 caption-painting pairs collected manually from Feng Zikai's paintings and 89,204 poem-painting pairs collected automatically from the web. We expect the former to help learning the artist painting style as it containshis most paintings, and the latter to help learning the semantic relevance between poems and paintings. Further, we analyze Paint4Poem regarding poem diversity, painting style, and the semantic relevance between poems and paintings. We create abenchmark for Paint4Poem, we train two representative text-to-image generation models, AttnGAN and MirrorGAN, and evaluate theirperformance regarding painting pictorial quality, painting stylistic relevance, and semantic relevance between poems and paintings.The results indicate that the models are able to generate paintings that have good pictorial quality and mimic Feng Zikai's style, but thereflection of poem semantics is limited. The dataset also poses many interesting research directions on this task, including transferlearning, few-shot learning, text-to-image generation for low-resource data etc. The dataset is publicly available.



# Summary. An optional shortened abstract.
# summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2109.11682'
url_code: 'https://github.com/paint4poem/paint4poem'
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
