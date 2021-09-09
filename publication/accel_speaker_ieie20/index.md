---
title: "Audio Compression Accelerator Design for Improving the Response Time of AI Speakers"
authors:
- hunjong-lee
- Junhwan Yoo
- admin
date: "2020-08-17T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-08-17T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["10"]

# Publication name and optional abbreviated publication name.
publication: "*Annual Summer Conference of IEIE*"
publication_short: "*IEIE '20*"

abstraction: "Response time is one of the critical performance factors of artificial intelligence (AI) speakers. The internet network delays and the processing time on cloud server infrastructure dominate the response delays of AI speakers. The network delay is proportional to the size of packets that include the recorded queries. Normally this recorded sound data is not compressed since compression processes can be a heavy burden for the wimpy processors embedded in AI speakers.
In this work we design an audio compression accelerator which can reduce the packet size of user queries. We implement the proposed accelerator on the FPGA-based SoC development board. Our evaluation reveals that the overall response time of an AI speaker is effectively reduced with the audio compression accelerator."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac #convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Accelerator
- Compression
- FPGA
featured: false

links:
- name: Slide Show
  url: https://filedn.com/luEeJVCCazShDlU4ibloXvu/publication/gpu_apcm_isca17/gpu_apcm_isca17_slides.ppsx
url_pdf: https://filedn.com/luEeJVCCazShDlU4ibloXvu/publication/gpu_apcm_isca17/gpu_apcm_isca17.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: https://filedn.com/luEeJVCCazShDlU4ibloXvu/publication/gpu_apcm_isca17/gpu_apcm_isca17_slides.pdf
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  caption: 'A cache management scheme of APCM'
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
