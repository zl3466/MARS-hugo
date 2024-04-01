---
title: "Dataset"
description: "Recipes, guides, and tutorials for Blowfish"

cascade:
  showDate: false
  showAuthor: false
  invertPagination: true
---

---
## Vehicle Setup
![vehicle setup](/img/vehicle_setup.jpg)

{{< katex >}}
## Sensor Specifications
| Sensor                        | Details                                                                                                                                       |
|-------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|
| 1 \\(\times\\) LiDAR          | 10Hz, 128 channel, horizontal FoV \\(360^\circ\\), vertical FoV \\(40^\circ\\)                                                                |
| 3 \\(\times\\) RGB Camrea     | 10Hz, original resolution \\(1440 \times 928\\), sampled to \\(720 \times 464\\), Horizontal FoV \\(60^\circ \\), Vertical FoV \\(40^\circ\\) |
| 3 \\(\times\\) Fisheye Camrea | 10Hz, original resolution \\(1240 \times 728\\), sampled to \\(620 \times 364\\), horizontal FoV \\(140^\circ\\), vertical FoV \\(88^\circ\\) |
| 1 \\(\times\\) IMU            | 10Hz, velocity, angular velocity, acceleration                                                                                                |
| 1 \\(\times\\) GPS            | 10Hz, longitude, latitude, elevation                                                                                                          |


---

[//]: # ({{< lead >}})

[//]: # (Multitraversal, multiagent, multimodal)

[//]: # ({{< /lead >}})

## Dataset

We curate two subsets in MARS: one facilitates collaborative driving with multiple vehicles simultaneously present at the same location, and the other enables memory retrospection through asynchronous traversals of the same location by multiple vehicles.

---
