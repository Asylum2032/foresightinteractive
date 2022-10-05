---
title: Scenario Title
layout: single
permalink: /template/
header:
    overlay_image: /assets/images/image_yellow.jpg
toc: true
toc_label: "Scenario Title"
toc_icon: "cog"    
persona_1:
  - image_path: /assets/images/image_yellow.jpg
    title: "Placeholder Persona 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: /
    btn_label: "Read More"
    btn_class: "btn--primary"
persona_2:    
  - image_path: /assets/images/image_yellow.jpg
    title: "Placeholder Persona 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: /
    btn_label: "Read More"
    btn_class: "btn--primary"
---

# Heading 1

Some text.

## Heading 2

Some more text.

{% include feature_row id="persona_1" type="left" %}

{% include feature_row id="persona_2" type="left" %}