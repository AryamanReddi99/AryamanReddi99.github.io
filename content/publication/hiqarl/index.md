---
title: 'Dynamic Obstacle Avoidance with Bounded Rationality Adversarial Reinforcement Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Jose-Luis Holgado-Alvarez
  - admin
  - Carlo D'Eramo

# Author notes (optional)
author_notes:


date: '2024-11-06'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-11-06'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: Workshop Poster in *Conference on Robot Learning*
publication_short: In *CORL*

abstract: Reinforcement Learning (RL) has proven largely effective in obtaining stable locomotion gaits for legged robots. However, designing control algorithms which can robustly navigate unseen environments with obstacles remains an ongoing problem within quadruped locomotion. To tackle this, it is convenient to solve navigation tasks by means of a hierarchical approach with a low-level locomotion policy and a high-level navigation policy. Crucially, the high-level policy needs to be robust to dynamic obstacles along the path of the agent. In this work, we propose a novel way to endow navigation policies with robustness by a training process that models obstacles as adversarial agents, following the adversarial RL paradigm. Importantly, to improve the reliability of the training process, we bound the rationality of the adversarial agent resorting to quantal response equilibria, and place a curriculum over its rationality. We called this method Hierarchical policies via Quantal response Adversarial Reinforcement Learning (Hi-QARL). We demonstrate the robustness of our method by benchmarking it in unseen randomized mazes with multiple obstacles. To prove its applicability in real scenarios, our method is applied on a Unitree GO1 robot in simulation. 

# Summary. An optional shortened abstract.
summary: Reinforcement Learning (RL) has proven largely effective in obtaining stable locomotion gaits for legged robots. However, designing control algorithms which can robustly navigate unseen environments with obstacles remains an ongoing problem within quadruped locomotion. To tackle this, it is convenient to solve navigation tasks by means of a hierarchical approach with a low-level locomotion policy and a high-level navigation policy. Crucially, the high-level policy needs to be robust to dynamic obstacles along the path of the agent. In this work, we propose a novel way to endow navigation policies with robustness by a training process that models obstacles as adversarial agents, following the adversarial RL paradigm. Importantly, to improve the reliability of the training process, we bound the rationality of the adversarial agent resorting to quantal response equilibria, and place a curriculum over its rationality. We called this method Hierarchical policies via Quantal response Adversarial Reinforcement Learning (Hi-QARL). We demonstrate the robustness of our method by benchmarking it in unseen randomized mazes with multiple obstacles. To prove its applicability in real scenarios, our method is applied on a Unitree GO1 robot in simulation. 

tags:
  - Robot Learning
  - Adversarial Reinforcement Learning

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2503.11467'
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
<!-- 
{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
