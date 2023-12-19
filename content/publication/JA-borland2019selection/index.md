---
title: "Selection bias tracking and detailed subset comparison for high-dimensional data"
authors:
- David Borland
- admin
- Jonathan Zhang
- Joshua Shrestha
- Daivd Gotz
author_notes:

date: "2019-08-20T00:00:00Z"
doi: "10.1109/TVCG.2019.2934209"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Visualization and Computer Graphics ( Volume: 26, Issue: 1, January 2020)*"
publication_short: ""

abstract: The collection of large, complex datasets has become common across a wide variety of domains. Visual analytics tools increasingly play a key role in exploring and answering complex questions about these large datasets. However, many visualizations are not designed to concurrently visualize the large number of dimensions present in complex datasets (e.g. tens of thousands of distinct codes in an electronic health record system). This fact, combined with the ability of many visual analytics systems to enable rapid, ad-hoc specification of groups, or cohorts, of individuals based on a small subset of visualized dimensions, leads to the possibility of introducing selection bias-when the user creates a cohort based on a specified set of dimensions, differences across many other unseen dimensions may also be introduced. These unintended side effects may result in the cohort no longer being representative of the larger population intended to be studied, which can negatively affect the validity of subsequent analyses. We present techniques for selection bias tracking and visualization that can be incorporated into high-dimensional exploratory visual analytics systems, with a focus on medical data with existing data hierarchies. These techniques include (1) tree-based cohort provenance and visualization, including a user-specified baseline cohort that all other cohorts are compared against, and visual encoding of cohort “drift”, which indicates where selection bias may have occurred, and (2) a set of visualizations, including a novel icicle-plot based visualization, to compare in detail the per-dimension differences between the baseline and a user-specified focus cohort. These techniques are integrated into a medical temporal event sequence visual analytics tool. We present example use cases and report findings from domain expert user interviews.

# Summary. An optional shortened abstract.
summary: Hierarchical visualization system for high dimensional dataset using tree-based cohort provenance, focused and excluded group comparison and novel icicle-plot for bias detection in details.

tags:
- High-dimensional visualization, visual analytics, cohort selection, medical informatics, selection bias
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8807213'
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
# slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
