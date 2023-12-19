---
title: "Visualization model validation via inline replication"
authors:
- David Gotz
- admin
- David Borland
author_notes:

date: "2019-01-25T00:00:00Z"
doi: "10.1177/1473871618821747"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Information Visualization, Volume 18, Issue 4*"
publication_short: ""

abstract: Data visualizations typically show a representation of a data set with little to no focus on the repeatability or generalizability of the displayed trends and patterns. However, insights gleaned from these visualizations are often used as the basis for decisions about future events. Visualizations of retrospective data therefore often serve as “visual predictive models.” However, this visual predictive model approach can lead to invalid inferences. In this article, we describe an approach to visual model validation called Inline Replication. Inline Replication is closely related to the statistical techniques of bootstrap sampling and cross-validation and, like those methods, provides a non-parametric and broadly applicable technique for assessing the variance of findings from visualizations. This article describes the overall Inline Replication process and outlines how it can be integrated into both traditional and emerging “big data” visualization pipelines. It also provides examples of how Inline Replication can be integrated into common visualization techniques such as bar charts and linear regression lines. Results from an empirical evaluation of the technique and two prototype Inline Replication–based visual analysis systems are also described. The empirical evaluation demonstrates the impact of Inline Replication under different conditions, showing that both (1) the level of partitioning and (2) the approach to aggregation have a major influence over its behavior. The results highlight the trade-offs in choosing Inline Replication parameters but suggest that using n=5 partitions is a reasonable default.

# Summary. An optional shortened abstract.
summary: Inline Replication as a new visual analytics pipeline to bootstrap big data into agreeable aggregations during high dimensional data analysis. 

tags:
- Visual analytics, information visualization, replication, validation, prediction
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://journals.sagepub.com/doi/epub/10.1177/1473871618821747'
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
#   slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
