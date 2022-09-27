---
title: Frontier Semantic Exploration for Visual Target Navigation
summary: The priors represented by scene graph are incorporated in deep reinforcement learning model using R-GCN on Habitat platform.
tags:
- RL
date: "2020-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart


# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

Abstract: Visual target navigation is very important for autonomous robots as it is closely related to high-level task. To find a special object in indoor environments, classical and learning-based approaches are fundamental components of navigation that they have been investigated thoroughly by researchers. However, due to the difficulty in the representation of complicated scenes and the learning of navigational policy, the problem is still the core challenge for previous methods in large unknown scenes. Hence, we propose a novel framework for visual target navigation based on the frontier semantic policy. In the proposed framework, the semantic map and the frontier map are built from current observation of the environment. Based on the features of the maps, the deep reinforcement learning is used to learn a navigational policy. The policy can be used to select a frontier from the map as long-term goal to explore the environment efficiently based on the object category. Experiments on Gibson and Habitat-Matterport 3D demonstrate that the proposed framework significantly outperforms existing modular map-based methods in terms of success rate and efficiency, and a demonstration is also provided to verify the applicability in applying to the real world transfer. The supplementary video can be accessed via the following link: \url{https://yubangguo.com/project/Frontier-Semantic-Exploration}.

The total code of target navigation can be found in https://github.com/ybgdgh/Frontier-Semantic-Exploration.



{{< figure src="framework.jpg" title="The framework of our approach." lightbox="true" >}}

{{< figure src="system_2.jpg" title="The process of the Frontiers." lightbox="true" >}}

{{< figure src="experiment.jpg" title="Viausl target navigation experiment in Habitat simulator to find a couch in different timesteps." lightbox="true" >}}

{{< figure src="system_3.jpg" title="Invalid Action Masking" lightbox="true" >}}

<!-- {{< video library="1" src="stair.mp4" controls="yes" >}} -->

{{< video library="1" src="ICRA23_0434_VI_i.mp4" controls="yes" >}}
