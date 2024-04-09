---
title: Large Language Model
summary: Large language models (LLMs) are advanced artificial intelligence systems capable of understanding, generating, and engaging in human-like text-based conversations across a wide range of topics and languages. Our research focuses on： safety, hallucination evaluation and elimination, model compression, and medical applications.
tags:
  - LLM
date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Schematic diagram of the development route of LLM.
  focal_point: Smart

links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
 #   url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

### **Safety in LLMs**

Safety is a paramount concern in the development and deployment of LLMs. It encompasses a range of issues from preventing the model from generating harmful, biased, or misleading information to ensuring data privacy and security. Techniques to enhance LLM safety include:

- **Content Filtering and Moderation**: Implementing algorithms to detect and mitigate the generation of inappropriate content.
- **Bias Mitigation**: Training models on diverse datasets and employing techniques to reduce biases in model outputs.
- **Robustness and Reliability**: Ensuring LLMs can handle edge cases and do not produce nonsensical or harmful outputs in unexpected situations.
- **Data Privacy**: Ensuring that the training process and data handling comply with data protection laws and ethical guidelines, particularly concerning user interactions.

### **Mixture of Experts (MoE)**

Mixture of Experts is a model architecture that scales LLMs by distributing parts of the computation across multiple expert networks, each specialized in different types of information or tasks. This allows for more efficient processing and the ability to scale to larger models without linear increases in computational requirements. Key aspects include:

- **Dynamic Routing**: Incoming tasks or inputs are dynamically directed to the most relevant experts, allowing the model to leverage specialized knowledge effectively.
- **Scalability**: MoE enables scaling model capacity more efficiently, as not all parameters are active simultaneously, reducing computation for any given task.
- **Expert Specialization**: This architecture fosters specialization, where different experts can become highly adept at handling specific types of information or tasks, improving overall performance and efficiency.

### **Medical Applications of LLMs**

In the medical field, LLMs offer transformative potential, from enhancing clinical decision support to automating administrative tasks and providing patient care:

- **Clinical Decision Support**: LLMs can analyze medical literature, patient data, and clinical guidelines to provide up-to-date recommendations, differential diagnoses, and treatment options.
- **Medical Literature and Research**: They can assist in the review and synthesis of vast amounts of medical research, identifying trends, and generating insights.
- **Patient Interaction**: LLMs can be used for patient education, answering queries, and even in therapeutic contexts, providing mental health support through conversational agents.
- **Administrative Automation**: Automating documentation, coding, and billing processes, reducing the administrative burden on healthcare professionals.
