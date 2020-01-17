+++
# Date this page was created.
date = "2019-01-01"

# Project title.
title = "Dynamic Resource Allocation for Mass Event Hotspots"

# Project summary to display on homepage.
summary = "To deploy UAV-mounted small cells and allocate wireless resources"

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "rdsc.jpg"

# Optional image to display on project detail page (relative to `static/img/` folder).
image = ""

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["5G/6G","HetNet","small cells","spectrum sharing","machine learning"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

+++

In the era of 5G mobile communications and Internet of Things (IoT), each macro-cell can be densely overlaid with small cells, so that mobile users or connected things are served by a heterogeneous network (HetNet). It is straightforward to deploy small cells for indoor hotspots such as homes or offices, but usually not for outdoor hotspots to support, e.g., public gatherings or sporting events. As the use of wireless devices outdoors is becoming a daily necessity, it has received a growing interest in augmenting macro-cell coverage for target spots that are wide-open yet short-lived. A further improvement of outdoor coverage is necessary when user devices are brought together in a short time and cause a burst increase in macro-cell traffic, thus leading to a supply-demand mismatch. It commonly occurs that lots of user devices are temporarily gathered for broadband or IoT services. However, it can be very costly or even impossible to fully and persistently cover an outdoor hotspot with small cells. Recently, a promising innovation is to mount small base stations (SBSs) on movable and controllable platforms, such as unmanned aerial vehicles (UAVs) or unmanned ground vehicles (UGVs). Under vehicular mobility, UAV/UGV-mounted small cells are rapidly deployable in case macro-cell base stations (MBSs) are overloaded, or even damaged or destroyed. 

On-demand deployment of UAV/UGV-mounted small cells plays a key role in augmenting macro-cell coverage for outdoor hotspots, but the issues of dynamic resource allocation have to be emphasized in the uplink. For example, a typical downlink-to-uplink ratio of mobile devices is 10:1, but it can become 1:3 during mass events along with a tenfold increase in uplink traffic, due to the popularity of social media. To handle intensive uploading of user/machine-generated data, limited wireless spectrum has to be shared and reused by small cells efficiently and effectively. Therefore, organizing a two-tier HetNet outdoors necessitates inter-cell spectrum sharing, and we mainly focus on co-tier spectrum sharing among small cells. This is different from a typical scenario in that network performance is valued more in the uplink than in the downlink. 

However, we have to address the following challenges. First, our approach has to jointly optimize small cell deployment and uplink resource allocation. In addition to the 3D placement of movable small cells to cover an outdoor hotspot, it is also necessary to study the establishment of uplink transmissions to meet user needs. Specifically, the problem of inter-cell spectrum sharing involves decision making on four aspects, including small cell placement, user-cell association, channel resource allocation, and transmit power control. Second, our approach has to be responsive to initially unknown and varying demands of user devices for uplink transmissions. It is common in an outdoor hotspot that movable small cells can only selectively fulfill a part of user demands for a limited period of time, but the distribution of user demands is not known a priori and is even ever-changing. Thus, the joint optimization problem has to be solved in a user-centric, online manner. Third, our approach has to be applicable to a resource-constrained cellular system. Although the base stations in two tiers of a HetNet can work as decision-making entities, the user-centric, online joint optimization to be performed can be too complex for either an MBS or an SBS. Any entity can suffer from limited computing, energy, and storage resources. Besides, it is already hard to derive a real-time solution to such a complex problem even given sufficient resources.


