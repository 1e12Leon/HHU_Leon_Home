---
title: '无人机视角下轻量型人脸检测与识别研究'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin

# Author notes (optional)
author_notes:
  - 'Equal contribution'

date: '2022-06-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-06-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['7']

# Publication name and optional abbreviated publication name.
publication: In *Hohai University*
publication_short: In *HHU*

abstract: Face detection and recognition from the UAV perspective can be used in a variety of complex scenarios, such as urban counter-terrorism and missing person searches, where the picture is clear enough. To this end, this paper investigates lightweight face detection and recognition methods for the UAV perspective, working as follows.
Through the study of previous research, this topic reproduces the lightweight RetinaFace face detection algorithm with MobileNetv1-0.25 as the backbone; then the FaceNet algorithm is used as the research object, and a lightweight FaceNet face recognition model based on the improvement of MobileNet is designed, and the combination of the two lightweight models achieves the real-time detection effect.A drone view face video dataset with a size of 36.8GB and 72 people was constructed for the training and testing of the model.In addition, a human-computer interactive UAV face detection and recognition system based on PyQt5 was developed based on the DJI Tello UAV for user-friendly use. Through relevant experiments, it is known that the model in this paper can meet the real-time performance of face detection and recognition tasks, and also achieve good results in terms of accuracy.


# Summary. An optional shortened abstract.
summary: Deep learning; UAV face detection; UAV face recognition; PyQt Development

tags: []

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
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
