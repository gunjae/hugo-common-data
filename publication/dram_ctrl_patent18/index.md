---
title: "Increasing Read Pending Queue Capacity to Increase Memory Bandwidth"
authors:
- admin
- Vivek Kozhikkottu
- Shankar Ganesh Ramasubramanian
- Christopher B. Wilkerson
date: "2018-07-05T00:00:00Z"
doi: 

# Schedule page publish date (NOT publication's date).
publishDate: "2018-07-05T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["8"]

# Publication name and optional abbreviated publication name.
publication: "*Patent (US)*"
publication_short: "*Patent (US)*"

abstract: "Devices, systems, and methods for increasing the size of a read pending queue (RPQ) in a memory controller are described. An example of increasing the RPQ size can include receiving, at a memory controller, a read request for data in a memory having a physical address identification (ID) including row and column ID, performing a lookup of the RPQ for an entry having a pending read transaction with a physical address ID having the same row ID as the incoming read request, and, if the RPQ lookup returns a hit, appending the incoming read request's column ID to the physical address ID of the pending read transaction to form an appended read transaction. The appending read transaction can then be queued and processed sequentially, while occupying a single RPQ entry."

# Summary. An optional shortened abstract.
summary: Publication of US20180188976A1

tags:
- DRAM
- Memory Controller
featured: true

links:
- name: Slide Show
  url: https://filedn.com/luEeJVCCazShDlU4ibloXvu/publication/sec_victim_date22/sec_victim_date22_slides.ppsx
url_pdf: https://filedn.com/luEeJVCCazShDlU4ibloXvu/publication/sec_victim_date22/sec_victim_date22.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: https://filedn.com/luEeJVCCazShDlU4ibloXvu/publication/sec_victim_date22/sec_victim_date22_slides.pdf
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
#  caption: 'US 2020/0310690 A1'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides:
---
