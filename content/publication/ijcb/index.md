---
title: "IHashNet: Iris Hashing Network based on efficient multi-index hashing"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Avantika Singh
- Pratyush Gaurav
- admin
- Aditya Nigam
- Rameshwar Pratap Yadav

date: "2020-07-01T00:00:00Z"
# doi: "2021-01-06"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-06-30T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In 2020 IEEE International Joint Conference on Biometrics (IJCB)
publication_short: In *IJCB 2020*

abstract: Massive biometric deployments are pervasive in today's world. But despite the high accuracy of biometric systems, their computational efficiency degrades drastically with an increase in the database size. Thus, it is essential to index them. Here, in this paper, we propose an iris indexing scheme using real-valued deep iris features binarized to iris bar codes (IBC) compatible with the indexing structure. Firstly, for extracting robust iris features, we have designed a network utilizing the domain knowledge of ordinal filtering and learning their nonlinear combinations. Later these real-valued features are binarized. Finally, for indexing the iris dataset, we have proposed a M_com loss that can transform the binary feature into an improved feature compatible with the Multi-Index Hashing scheme. This M_com loss function ensures the equal distribution of Hamming distance among all the contiguous disjoint sub-strings. To the best of our knowledge, this is the first work in the iris indexing domain that presents an end-to-end iris indexing structure. Experimental results on four datasets are presented to depict the efficacy of the proposed approach.

# Summary. An optional shortened abstract.
summary: In this paper, we propose an iris indexing scheme using real-valued deep iris features binarized to iris bar codes (IBC) compatible with the indexing structure. For indexing the iris dataset, we have proposed a loss that can transform the binary feature into an improved feature compatible with the Multi-Index Hashing scheme.

tags: [cryptography, feature extraction, Hamming codes, image coding ,iris recognition]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9304925/'
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
