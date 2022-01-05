---
title: "Analyzing Data Cache Performance of Modern GPU Architecture"
authors:
- jonghyun-jeong
- Yunho Oh
- admin
date: "2021-12-20T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-11-25T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["10"]

# Publication name and optional abbreviated publication name.
publication: "*Korea Software Congress*"
publication_short: "*KSC '21*"

abstract: "Graphics processing unit (GPU)는 그래픽 어플리케이션의 처리 뿐만 아니라 최근 machine learning, big data analytics 등의 대규모 병렬처리를 요구하는 어플리케이션의 처리에 널리 사용되고 있다. GPU는 많은 수의 쓰레드를 동시에 실행하는 병렬처리 구조를 가지고 있다. 이 때문에 많은 메모리 요청이 단시간 내에 발생되어 메모리 계층구조의 자원이 소진되고 데이터 캐시가 비효율적으로 사용되는 문제가 있었다. 최신 GPU 아키텍처에서는 이러한 문제를 해결하기 위해 streaming cache라고 불리는 새로운 캐시 구조를 적용하여 데이터 캐시의 성능 저하 요소를 줄였다. 본 연구에서는 최신 GPU 시뮬레이터를 사용하여 streaming cache의 성능을 기존 캐시와 자세히 비교하여 streaming cache의 특성을 밝히고 있다. 본 연구에서는 streaming cache가 데이터 캐시의 congestion은 해결하지만 memory congestion이 interconnection network 단으로 옮겨갈 수 있음을 밝혀냈다. 본 연구를 통하여 streaming cache가 최신 GPU 메모리 시스템에서 미치는 영향을 분석하여 최신 GPU 아키텍처의 메모리 시스템에서 발생할 수 있는 성능 문제점들에 대해서 제시한다."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac #convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- GPU
- Cache
- Characteristics
featured: false

links:
- name: Slide Show
  url: https://filedn.com/luEeJVCCazShDlU4ibloXvu/publication/gpu_cache_ksc21/gpu_cache_ksc21_slides.ppsx
url_pdf: https://filedn.com/luEeJVCCazShDlU4ibloXvu/publication/gpu_cache_ksc21/gpu_cache_ksc21.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: https://filedn.com/luEeJVCCazShDlU4ibloXvu/publication/gpu_cache_ksc21/gpu_cache_ksc21_slides.pdf
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  caption: 'Memory subsystems by GPU architecture generations'
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
