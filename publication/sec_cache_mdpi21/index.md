---
title: "RT-Sniper: A Low-Overhead Defense Mechanism Pinpointing Cache Side-Channel Attacks"
authors:
- Minkyu Song
- Junyeon Lee
- Taeweon Seo
- admin
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2021-11-10T00:00:00Z"
doi: "10.3390/electronics10222748"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-11-10T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*MDPI Electronics* (Volume: 10)"
publication_short: "*MDPI Electronics*"

abstract: Since cache side-channel attacks have been serious security threats to multi-tenant systems, there have been several studies to protect systems against the attacks. However, the prior studies have limitations in determining only the existence of the attack and/or occupying too many computing resources in runtime. We propose a low-overhead pinpointing solution, called RT-Sniper, to overcome such limitations. RT-Sniper employs a two-level filtering mechanism to minimize performance overhead. It first monitors hardware events per core and isolates a suspected core to run a malicious process. Then among the processes running on the selected core, RT-Sniper pinpoints a malicious process through a per-process monitoring approach. With the core-level filtering, RT-Sniper has an advantage in overhead compared to the previous works. We evaluate RT-Sniper against Flush+Reload and Prime+Probe attacks running SPEC2017, LMBench, and PARSEC benchmarks on multi-core systems. Our evaluation demonstrates that the performance overhead by RT-Sniper is negligible (0.3% for single-threaded applications and 2.05% for multi-threaded applications). Compared to the previous defense solutions against cache side-channel attacks, RT-Sniper exhibits better detection performance with lower performance overhead.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Security
- Malware Detection
- Cache Side-Channel Attacks
- Low-Overhead
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://filedn.com/luEeJVCCazShDlU4ibloXvu/publication/sec_cache_mdpi21/sec_cache_mdpi21.pdf
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
  caption: 'RT-Sniper mechanism'
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
slides:
---

#{{% callout note %}}
#Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
#{{% /callout %}}
#
#Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
