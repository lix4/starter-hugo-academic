---
title: "Real-Time Idling Vehicles Detection Using Combined Audio-Visual
Deep Learning"
authors:
- admin
- Tristalee Mangin
- Surojit Saha
- Evan Blanchard
- Dillon Tang
- Henry Poppe
- Nathan Searle
- Ouk Choi
- Kerry Kelly
- Ross Whitaker
date: "2023-05-22"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: 'Combustion vehicle emissions contribute to poor
air quality and release greenhouse gases into the atmosphere,
and vehicle pollution has been associated with numerous
adverse health effects. Roadways with extensive waiting and/or
passenger drop off, such as schools and hospital drop-off zones,
can result in high incidence and density of idling vehicles. This
can produce micro-climates of increased vehicle pollution. Thus,
the detection of idling vehicles can be helpful in monitoring
and responding to unnecessary idling and be integrated into
real-time or off-line systems to address the resulting pollution.
In this paper we present a real-time, dynamic vehicle idling
detection algorithm. The proposed idle detection algorithm and
notification rely on an algorithm to detect these idling vehicles.
The proposed method relies on a multi-sensor, audio-visual,
machine-learning workflow to detect idling vehicles visually
under three conditions: moving, static with the engine on, and
static with the engine off. The visual vehicle motion detector
is built in the first stage, and then a contrastive-learning-based
latent space is trained for classifying static vehicle engine sound.
We test our system in real-time at a hospital drop-off point in
Salt Lake City. This in-situ dataset was collected and annotated,
and it includes vehicles of varying models and types. The
experiments show that the method can detect engine switching
on or off instantly and achieves 71.01 mean average precision
(mAP).'

# Summary. An optional shortened abstract.
summary: 'An audio-visual workflow for idling vehicle detection'

tags:
- Source Themes
featured: true

# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: http://arxiv.org/pdf/1512.04133v1
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
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

{{% callout note %}}
<!-- Create your slides in Markdown - click the *Slides* button to check out the example. -->
{{% /callout %}}

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
