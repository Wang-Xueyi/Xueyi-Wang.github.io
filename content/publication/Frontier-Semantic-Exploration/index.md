---
title: "Frontier Semantic Exploration for  Visual Target Navigation"
authors:
- Bangguo Yu
- Hamidreza Kasaei
- Ming Cao
date: "2023-01-16T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-01-016T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: *2023 IEEE International Conference on Robotics and Automation*
publication_short: In *ICRA2023*

abstract: This work focuses on the problem of visual target  navigation, which is very important for autonomous robots as it is closely related to high-level tasks. To find a special object in unknown environments, classical and learning-based approaches are fundamental components of navigation that have been investigated thoroughly in the past. However, due to the difficulty in the representation of complicated scenes and the learning of the navigation policy, previous methods are still not adequate, especially for large unknown scenes. Hence, we propose a novel framework for visual target navigation using the frontier semantic policy. In this proposed framework, the semantic map and the frontier map are built from the current observation of the environment. Using the features of the maps and object category, deep reinforcement learning enables to learn a frontier semantic policy which can be used to select a frontier cell as a long-term goal to explore the environment efficiently. Experiments on Gibson and Habitat-Matterport 3D (HM3D) demonstrate that the proposed framework significantly outperforms existing map-based methods in terms of success rate and efficiency. Ablation analysis also indicates that the proposed approach learns a more efficient exploration policy based on the frontiers. A demonstration is provided to verify the applicability of applying our model to real-world transfer.

# Summary. An optional shortened abstract.
summary: (Accepted by ICRA2023) high-level human-robot interaction tasks, visual target navigation
tags:
- Reinforcement Learning
featured: true

# links:
# - name: Custom Link
#   url: = "https://sites.google.com/view/fsevn"
# url_pdf: url = "files/cv.pdf"
url_code: 'https://github.com/ybgdgh/Frontier-Semantic-Exploration'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
url_source: 'https://sites.google.com/view/fsevn'
url_video: 'https://youtu.be/NpP0jRdFZoo'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'target navigation'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- target navigation

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

