---
title: "Revealing Characteristics of GCN Inference Models Using a GPU Profiler"
authors:
- inje-kim
- admin
date: "2021-06-25T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-06-25T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["10"]

# Publication name and optional abbreviated publication name.
publication: "*Korea Computer Congress*"
publication_short: "*KCC '21*"

abstract: "Graph Convolutional Neural Network (GCN)은 그래프 구조를 이용한 인공 신경망 (Graph Neural Network, GNN) 중의 하나로서 소셜 네트워크 분석 및 소비자 성향 분석, 추천 시스템 등의 여러 응용 분야에 이용될 수 있다. GCN은 비유클리드형 자료 구조의 형태를 가지는 그래프 구조에 대한 데이터 처리를 요구하기 때문에 기존의 Deep Neural Network (DNN)에 사용되는 데이터와는 차이점을 가지고 있다. 그렇기 때문에, GCN을 기존의 DNN을 처리하는 데에 주로 쓰이는 하드웨어 구조에서 실행했을 때의 특성을 분석하는 것은 향후 효과적인 GCN용 알고리즘 및 하드웨어를 설계하는 데에 있어서 필수적이다. 본 연구에서는 인공 신경망 구조를 처리하는 데에 주로 쓰이는 GPU에서 여러가지 GCN 추론 알고리즘을 실행하고 이를 GPU 프로파일러로 분석하여 해당 하드웨어 구조에서 GCN 추론 커널이 가지는 특성을 밝히고 있다. 본 연구에서는 GCN 추론 과정에 쓰이는 커널들이 크게 두 종류의 큰 차이를 보이는 특성을 보이는 커널들로 분류할 수 있음을 밝히고 있으며, 이러한 특성에 기반하여 GCN의 커널들이 GPU에서 실행 엔진과 캐시 메모리와 같은 하드웨어 자원을 비효율적으로 사용하고 있음을 밝혀내었다. 본 연구를 통하여 GCN의 최적화 방법 및 GCN을 효율적으로 실행하기 위한 구조적인 접근 방법에 대해서 도움을 줄 수 있다."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac #convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- GNN
- Profiling
- GPU
featured: false

links:
- name: Slide Show
  url: https://filedn.com/luEeJVCCazShDlU4ibloXvu/publication/gnn_profile_kcc21/gnn_profile_kcc21_slides.ppsx
url_pdf: https://filedn.com/luEeJVCCazShDlU4ibloXvu/publication/gnn_profile_kcc21/gnn_profile_kcc21.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: https://filedn.com/luEeJVCCazShDlU4ibloXvu/gnn_profile_kcc21/gnn_profile_kcc21_slides.pdf
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  caption: 'Memory System Characteristics of GCN Kernels'
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
