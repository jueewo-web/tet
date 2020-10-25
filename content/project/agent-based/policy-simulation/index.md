---
title: Policy Simulation
#subtitle: --
summary: agent-based strategies.
tags:
- Strategy
- Simulation
date: "2019-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  #caption: Photo by rawpixel on Unsplash
  caption: (c) by jueewo ventures
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/jwvntrs
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
slides: ""

gallery_item:
- album: gallery1
  image: abm_structure1.png
  caption: Model structure
- album: gallery1
  image: abm_structure2.png
  caption: Model communication & learning

- album: gallery2
  image: network1.png
  caption: Netlogo-Graphstream Interaction
- album: gallery2
  image: network2.png
  caption: Graphstream network
- album: gallery2
  image: network3.png
  caption: Project/Call structure
- album: gallery2
  image: network4.png
  caption: Consortia formation

---


## Agent-based simulation of policy making in highly interactive dynamic systems

This project is introducing a dynamic simulation framework to simulate and optimize decisions and policies. A hybrid (continuous & discrete) simulation core is used for the calculation of the interactive effects of heterogeneous actors. After the system is calibrated using learning algorithms, various scenarios are captured in a data model. The calibrated system is used as a decision support system for optimal policy making.


<!-- 
{{< figure src="pics/abm_structure1.png" caption="Model structure" >}}

{{< figure src="pics/abm_structure2.png" caption="Model communication & learning" >}} -->

The following images are showing the simulation structure: 

{{< gallery album="gallery1" >}}




### Features

#### Agent-based simulation
The core consists an agent-based simulation model which captures the interaction effect between the participants and the external control inputs.

#### Reverse Unsupervised Learning
The system is using a closed control loop to learn the effect of continuous influences and their effect. A constant stream of usage data is used to train and to recalibrate the model.

#### Continuous Interaction
The system offers a set of simple control handles. Any scenario can be set on the fly to determine their effect on the policy outcome. This immediate response is determined using the trained data model.

#### Decision Support
The calibrated system is able to predict policy interventions just in time.
Mobile and web-services can access the model to provide a seamless user experience and/or an integration into existing systems.


#### Example: Network and Consortia Formation 

<!-- {{< figure src="pics/network1.png" caption="Netlogo-Graphstream Interaction">}}

{{< figure src="pics/network2.png" caption="Graphstream network" >}}

{{< figure src="pics/network3.png" caption="Project/Call structure" >}}

{{< figure src="pics/network4.png" caption="Consortia formation" >}} -->

{{< gallery album="gallery2" >}}



````plain
This project has been funded by the EU
FP7 / DG Research & Innovation / RTD-B6-PP-00962-2013
````

---
