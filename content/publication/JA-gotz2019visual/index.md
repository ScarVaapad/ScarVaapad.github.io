---
title: "Visual Analysis of High-Dimensional Event Sequence Data via Dynamic Hierarchical Aggregation"
authors:
- David Gotz
- Jonathan Zhang
- admin
- Joshua Shrestha
- David Borland
author_notes:

date: "2019-08-01T00:00:00Z"
doi: "10.1109/TVCG.2019.2934661"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Visualization and Computer Graphics ( Volume: 26, Issue: 1, January 2020)*"
publication_short: ""

abstract: Temporal event data are collected across a broad range of domains, and a variety of visual analytics techniques have been developed to empower analysts working with this form of data. These techniques generally display aggregate statistics computed over sets of event sequences that share common patterns. Such techniques are often hindered, however, by the high-dimensionality of many real-world event sequence datasets which can prevent effective aggregation. A common coping strategy for this challenge is to group event types together prior to visualization, as a pre-process, so that each group can be represented within an analysis as a single event type. However, computing these event groupings as a pre-process also places significant constraints on the analysis. This paper presents a new visual analytics approach for dynamic hierarchical dimension aggregation. The approach leverages a predefined hierarchy of dimensions to computationally quantify the informativeness, with respect to a measure of interest, of alternative levels of grouping within the hierarchy at runtime. This information is then interactively visualized, enabling users to dynamically explore the hierarchy to select the most appropriate level of grouping to use at any individual step within an analysis. Key contributions include an algorithm for interactively determining the most informative set of event groupings for a specific analysis context, and a scented scatter-plus-focus visualization design with an optimization-based layout algorithm that supports interactive hierarchical exploration of alternative event type groupings. We apply these techniques to high-dimensional event sequence data from the medical domain and report findings from domain expert interviews.

# Summary. An optional shortened abstract.
summary: A new visual analytics approach that offers dynamic and interactive visualzations of temporal data with high dimensionality. 
tags:
- Temporal event sequence visualization, visual analytics, hierarchical aggregation, medical informatics
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8807220'
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
