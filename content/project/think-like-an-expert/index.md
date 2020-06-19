---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Think Like an Expert"
summary: "Decoding understanding of computer science concepts from student brains"
authors: []
tags: []
categories: []
date: 2020-06-14T16:47:49-04:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: "Link to preprint (bioRxiv)"
  url: https://www.biorxiv.org/content/10.1101/2020.05.05.079384v1
  icon_pack: fab
  #icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
{{< figure src="lecturesD.jpg" title="Predicting exam score from brain activity" numbered="false" lightbox="true" >}} 

### Decoding understanding from student brains ###


How do students understand and remember new information?
In [Think like an expert](https://www.biorxiv.org/content/10.1101/2020.05.05.079384v1), we measure understanding in student 🧠 and use it to predict and assess learning outcomes in a STEM course. The good news? Classmates are guide to success! 

Neural alignment among students during computer science lectures predicted performance in a final exam. For example, in the hippocampus, neural alignment to the rest of the class predicted overall exam scores weeks in advance. And during the exam, neural alignment tracked understanding of specific concepts in individual learners. Concepts that evoked better alignment with the experts - and with other students - were better understood. This could help design better courses, but for students, it might be more useful to know **why** a concept is difficult and how to understand it better. We found that we can probe students’ “knowledge structure”, pinpoint the problem and potentially say, “you struggle with recursion because you need to revisit loops”.

#### Methods:
- Functional MRI
- Multi-voxel pattern analysis (MVPA)
- Non-parametric statistics
