---
title: 'A matheuristic solution for efficient scheduling in dynamic truck–drone collaboration'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Dr. Jinqiu Zhao
  - admin
  - Dr. Binglei Xie
  - Dr. Gangyan Xu
  - Yongwu Liu

# Author notes (optional)
author_notes:
  - ''

date: '2024-12-27T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-12-27T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *Expert Systems with Applications*
publication_short: In *ESWA*

abstract: Unmanned aerial vehicles (UAVs), or drones, have great potential for emergency response operations in areas with vulnerable road networks and infrastructure. However, the low battery capacity restricts their quick, cost-effective, and efficient aerial transportation capabilities. To overcome this drawback, hybrid systems that combine trucks and drones have emerged as a promising solution. Nevertheless, the fixed-binding mode between trucks and drones in most studies tends to impair efficiency by limiting drones’ operational flexibility. This paper investigates a dynamic truck–drone collaboration (DTDC) strategy for efficient and flexible emergency response. This strategy enables drones to dynamically change take-off and landing locations on different trucks, which is beneficial in emergency scenarios with common road network disruptions. Despite its advantages, the DTDC strategy introduces additional complexity to the scheduling problem, resulting in a time-consuming solution. To enhance solution efficiency and improve the application prospects of this strategy, we propose a matheuristic to decouple DTDC’s multiple synchronization constraints, separating the scheduling problem into three decision-making processes: demand allocation, truck routing, and drone scheduling. Additionally, two alternative matheuristic algorithms are designed to target accuracy and computing efficiency, respectively. The empirical results indicate that the proposed heuristics outperform the state-of-the-art solver and several metaheuristics. A sensitivity analysis confirms that improvements in drone endurance and the strategic reservation of drone parking slots on trucks can significantly improve the DTDC strategy’s performance.

# Summary. An optional shortened abstract.
summary: Develops a matheuristic framework to address complex synchronization constraints in dynamic truck-drone collaboration.

tags:
  - Truck-UAV collaboration
  - Matheuristic

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    10.1016/j.eswa.2024.126218

# Custom links
links:
  - type: pdf
    url: "https://www.sciencedirect.com/science/article/pii/S0957417424030859"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false
---
