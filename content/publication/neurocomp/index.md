---
title: "A generic framework for deep incremental cancelable template generation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Avantika Singh
- admin
- Pratyush Gaurav
- Aditya Nigam

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-03-18T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In Neurocomputing
publication_short: In Neurocomputing

abstract: In a post-COVID-19 world, extensive study of deep learning-based biometric authentication techniques prompts the need to secure them. Further, the biometric data is assumed to be largely immutable; thus, if it is compromised, it is lost forever. Hence, reliable and secure biometric authentication is of utmost importance. In this paper, we address the security and privacy concerns of biometric templates generated via deep networks. We propose a cancelable biometric authentication approach. The framework consists of a  lightweight Convolutional Neural Network (CNN)  with few-shot enrollment for generating biometric templates. Further, for enhancing the discriminative power of biometric templates and to provide revocability, biometric templates are projected onto a  random subspace (based on user-specific key). Later projected biometric templates are mapped onto robust n-bit unique codes (using a KNN classifier) and protected via. SHA-3 hash digest. Moreover, a real-world biometric authentication system is always dynamic (users keep on changing). Thus we have also integrated phase-wise incremental learning within deep learning-based cancelable biometric authentication framework. This is the first work in which deep cancelable templates are generated incrementally to the best of our knowledge. We analyze the proposed scheme for its performance, and privacy preservation on three benchmarks constrained iris datasets and over one unconstrained iris dataset along with one publicly available knuckle dataset. Furthermore, it has been demonstrated that the proposed cancelable incremental framework strictly follows the four fundamental properties of cancelability viz. non-invertibility, unlinkability, revocability, and usability.

# Summary. An optional shortened abstract.
summary: We address the security and privacy concerns of biometric templates generated via deep networks. We propose a cancelable biometric authentication approach. The framework consists of a  lightweight Convolutional Neural Network (CNN)  with few-shot enrollment for generating biometric templates. This is the first work in which deep cancelable templates are generated incrementally to the best of our knowledge.

tags: [biometric template protection, cancelable biometrics, life long learning, memory aware synapses, phase wise incremental learning]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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
<!-- 
{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
