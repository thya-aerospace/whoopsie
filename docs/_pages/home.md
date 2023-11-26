---
title: "Whoopsie"
layout: splash
permalink: /
share: false
# date: 2023-10-23T10:53:40-06:00
header:
  overlay_color: "#000"
  overlay_filter: "0.3"
  overlay_image: /assets/images/robin-glauser-aSvBypuXGkc-unsplash.jpg
  # actions:
  #   - label: "Learn More"
  #     url: "/terms/"
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "A simple and scalable MQTT-based service status messaging protocol with integrated serialization for Cpp and Python"
# intro: 
#   - excerpt: 'Stats'

feature_howto:
  - image_path: /assets/images/whoopsie_architecture.png
    alt: "Whoopsie architecture diagram"
    title: "Build and host your own service messaging infrastructure"
    excerpt: '<pre>echo "whoopsie"<br>echo "hi"<br>echo "whoopsie"</pre>'
    url: "https://github.com/thya-aerospace/whoopsie/wiki" #"#TBD"
    btn_label: "Getting Started"
    btn_class: "btn--primary"

feature_product:
  - image_path: assets/images/pdf_prtot_snipped.PNG
    image_caption: "Whoopsie Protocol"
    alt: "Whoopsie Protocol"
    title: "Whoopsie Protocol"
    url: "/whoopsie-protocol/"
    excerpt: "short explanation of the standard here..."
    # btn_label: "TBD"
    # btn_class: "btn--primary"
  # - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
  #   alt: "placeholder image 2"
  #   title: "what"
  #   excerpt: "That thing here."
  #   url: "#test-link"
  #   btn_label: "TBD"
  #   btn_class: "btn--primary"
  # - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
  #   title: "what"
  #   excerpt: "That thing here."
  #   url: "#test-link"
  #   btn_label: "TBD"
  #   btn_class: "btn--primary"

# feature_company:
#   # - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
#     alt: "placeholder image 2"
#     title: "Companies that use it"
#     url: "#test-link" 
 
---

{% include feature_row id="feature_howto" type="left" %}
<!-- {% include feature_row_button id="feature_buttons" type="center"%} -->
{% include feature_row id="feature_product" type="right" %}
<!-- {% include feature_row id="feature_company" type="right" %} -->
<!-- {% include client-slider.html id="feature_company" %} -->
