---
title: "Whoopsie"
layout: splash
permalink: /
date: 2023-10-23T10:53:40-06:00
header:
  overlay_color: "#000"
  overlay_filter: "0.3"
  overlay_image: /assets/images/robin-glauser-aSvBypuXGkc-unsplash.jpg
  # actions:
  #   - label: "Learn More"
  #     url: "/terms/"
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "A simple and scalable MQTT-based service status messaging protocol with integrated serialization"
# intro: 
#   - excerpt: 'Stats'

feature_howto:
  - image_path: /assets/images/whoopsie_architecture.png
    alt: "Whoopsie architecture diagram"
    title: "Build and host your own service messaging infrastructure"
    excerpt: '
        <pre>echo "whoopsie"<br>echo "hi"</pre>
        <pre>echo "whoopsie"</pre>
        <pre>echo "whoopsie"</pre>'
    url: "https://github.com/thya-aerospace/whoopsie/wiki" #"#TBD"
    btn_label: "Getting Started"
    btn_class: "btn--primary"

# feature_buttons:
#   - title: "Statistics"
#   - btn_label: "30M Messages"
#     btn_class: "btn--inverse"
#   - btn_label: "100 Countries"
#     btn_class: "btn--inverse"
#   - btn_label: "3000 Users"
#     btn_class: "btn--inverse"
#   - btn_label: "3000 Users"
#     btn_class: "btn--inverse"


feature_product:
  - image_path: assets/images/whoopsie_architecture.png
    image_caption: "Whoopsie Architecture"
    alt: "Whoopsie Architecture"
    title: "whWhoopsie Architecture"
    excerpt: "<pre>
.post-title {
  margin: 0 0 5px;
  font-weight: bold;
  font-size: 38px;
  line-height: 1.2;
  and here's a line of some really, really, really, really long text, just to see how the PRE tag handles it and to find out how it overflows;
}
</pre>"
    url: "#n/a"
    btn_label: "TBD"
    btn_class: "btn--primary"
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
{% include feature_row id="feature_product" %}
<!-- {% include feature_row id="feature_company" type="right" %} -->
<!-- {% include client-slider.html id="feature_company" %} -->
