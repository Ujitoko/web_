---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Vibrator Transparency"
summary: "We define the ''vibrator transparent system'' as a control system that absorbs the difference in vibrator environments' frequency characteristics.
Therefore, with this system, it is possible to reproduce the output vibration by only reusing the input signals from vibrotactile signal assets."
authors: []
tags: []
categories: []
date: 2020-02-25T21:38:23+09:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

links:
- name: IEEE Haptics 2020
  url:
  icon_pack: fas
  icon: file-pdf

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
When an input command signal designed with one vibrator is reused with another vibrator with different frequency characteristics, there is a problem that the output vibration will differ.
Therefore, we propose the concept of ''vibrator transparency.''
We define the ''ibrator transparent system'' as a control system that absorbs the difference in vibrator environments' frequency characteristics.
The output vibration of the system does not depend on the change of the vibrator environment but depends only on the input signal.
Therefore, with this system, it is possible to reproduce the output vibration by only reusing the input signals from vibrotactile signal assets.
Inside the system, an adaptation process for the input signal is automatically executed.
To prove the feasibility of this concept, we verified the reproducibility of vibration
through both objective metrics and user study.
It was proved that the proposed system significantly improved the reproducibility of the vibrations compared with the conventional system for any vibrators and any input signals.
