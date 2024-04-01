---
title: 'Multi-Granularity Scene Graph-Enhanced Encoder-Decoder Language Model for Video-Grounded Dialogue Generation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Hongcheng Liu
  - Zhe Chen
  - Hui Li
  - Pingjie Wang
  - Yanfeng Wang
  - Yu Wang

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-04-01T00:00:00Z'
doi: '10.1109/ICASSP48485.2024.10447469'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-03-18T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2024 IEEE International Conference on Acoustics, Speech and Signal Processing*
publication_short: In *ICASSP 2024*

abstract: Generating dialogue grounded in videos requires a high level of understanding and reasoning about the visual scenes in the videos. However, existing large visual-language models are not effective due to their latent features and decoder-only structure, especially with respect to spatio-temporal relationship reasoning. In this paper, we propose a novel approach named MSG-BART, which enhances the integration of video information by incorporating a multi-granularity spatio-temporal scene graph into an encoder-decoder pre-trained language model. Specifically, we integrate the global and local scene graph into the encoder and decoder, respectively, to improve both overall perception and target reasoning capability. To further improve the information selection capability, we propose a multi-pointer network to facilitate selection between text and video. Extensive experiments are conducted on three video-grounded dialogue benchmarks, which show the significant superiority of the proposed MSG-BART compared to a range of state-of-the-art approaches.

# Summary. An optional shortened abstract.
summary: multi-granularity scene graph, multi-pointer network, video-grounded dialogue generation 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10447469?casa_token=DVlTj-aFvkkAAAAA:iOLRye5Js3MIrOiV9rsnPjiXkO0hmouBILmgQ3xnCMmW5Pwy7BV8Ae5bY36YzqLGL_BnZo6pqHm3'
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
  - Multimodal

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).