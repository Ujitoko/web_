---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "GAN-based Vibrotactile Design"
summary: "We propose a new generative model that realizes the vibrotactile generation automatically based on texture images or material attributes.
Our method can stop wasting time for hand-tuning vibrotactile signals and it promotes the rapid-design of vibrotactile signals."
authors: []
tags: []
categories: []
date: 2020-01-24T17:36:13+09:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Encoder and generator"
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
- name: IEEE ACCESS
  url: https://ieeexplore.ieee.org/document/8963970
  icon_pack: fas
  icon: file-pdf
- name: Eurohaptics 2018
  url: https://link.springer.com/chapter/10.1007/978-3-319-93399-3_3
  icon_pack: fas
  icon: file-pdf
- name: SIGGRAPH Asia 2018
  url: https://dl.acm.org/doi/10.1145/3275476.3275484
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


# Vibrotactile Design Productivity

Recently, consumer devices equipped with vibrotactile actuators such as Apple Watch have become wide-spread.
For example, there are touch pens, touchpads, and game controllers with vibrotactile
actuators around us, and we think of them as nothing
special.
Vibrotactile stimulation allows humans to perceive
the material properties of virtual surfaces.
If vibrotactile stimuli match the material attributes of visualized
surfaces in the application, the users perceive the textures
as more realistic.
Thus, tactile designers need to design vibrations carefully and how to design the vibrotactile stimuli is becoming essential.

The vibrotactile design process consists of preparation,
initial designing, and fine-tuning. It is known that the finetuning
phase occupies more than half of all workloads.
Thus, improving productivity in the fine-tuning phase will contribute to the improvement of all workloads.
However, there is no suitable tool for iteration and refinement while
there are existing tools for preparation and initial designing.
The difficulty in fine-tuning exists in the control of high-level material parameters such as rocky or metallic by changing low-level engineering parameters such as
frequency or amplitude.
The ability to use low-level engineering parameters to construct or evaluate for material characteristics is tacit knowledge that vibrotactile designers build over the years.
Based on these considerations, we set a goal of this study as providing a vibrotactile design method that enables non-expert designers to fine-tune vibrations with material-level
user-interfaces.
This study utilizes the Generative Adversarial Network (GAN) based vibration generator.

# Prototype Design Tool using GAN-based Automatic Generation

We made the prototype design tool.
With this tool, users can experience the rapid designing process of the vibrotactile stimuli for specific user interfaces or specific contents on applications.
Users receive the vibrotactile feedback by moving or tapping with a pen-type tactile device described above on a surface of a tablet device.
For designing UI components' tactile feedback, users can control parameters like material kinds or perceptual tactile words to generate suitable vibrotactile stimuli.
They can generate vibrotactile stimuli while touching and set it as a UI such as a button or a slider. For instance, by controlling the setting values of such parameters, we can generate vibrotactile stimuli like "rough metal" or "slippery wood."
In addition, for designing the 3D model's texture with vibrotactile stimuli, the system can automatically generate optimum virotactile feedback for the texture image that users apply to the model.
Users can touch and compare various textures, and if there is no suitable one, they can generate a texture and a vibrotactile stimulus by taking a picture with a camera, searching an image from the web, or sending an image that users have in their mobile phones to the system.

{{< video src="TactGAN_full.mp4" controls="yes" >}}
