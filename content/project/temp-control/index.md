---
title: 'Temperature control'
summary: "Getting all the ovens etc stable."
authors:
- jendrzejewski
# tags:
# - Teaching
lastmod: "2020-12-29T00:00:00Z"
featured: false
draft: false
tags:
- component
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
image:
  placement: 2
  caption: 'Caption'
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

A flask server that should simplify the logging of our experimental components. The details can be found [here](https://github.com/synqs/DeviceControlServer). Most of the time the components are Arduinos. The website assumes that the Arduinos are connected via ethernet. For the moment we have to following abilities:

- Add a few arduinos.
- Give setpoint and live temperature in overview.
- It shows data in a long list for the moment.
- The setpoint can be changed in the config page.
- The data can be exported to csv.
- PID values can be set from the interface.
