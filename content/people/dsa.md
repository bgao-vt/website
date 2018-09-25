+++
# Date this page was created.
date = "2015-09-11"

# Project title.
title = "Dynamic Spectrum Access"

# Project summary to display on homepage.
summary = "To achieve the coexistence of wireless networks for shared spectrum access"

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "dsa.jpg"

# Optional image to display on project detail page (relative to `static/img/` folder).
image = ""

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["dynamic spectrum access","opportunistic spectrum access","cognitive radio networks","spectrum sharing"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

+++

In accordance with the current fixed spectrum allocation policy, radio frequency bands have been allocated to diverse specific services and users by spectrum regulators, such as the Federal Communications Commission (FCC) in the United States and the Office of Communications (Ofcom) in the United Kingdom. In general, wireless spectrum is divided into two classes: licensed spectrum and unlicensed spectrum. On the one hand, unlicensed spectrum bands such as the industrial, scientific, and medical (ISM) bands (i.e., 902-928 MHz, 2.400-2.500 GHz, and 5.725-5.875 GHz) have become congested due to the popularity of personal wireless devices. On the other hand, considerable licensed spectrum bands such as the broadcast digital TV bands (i.e., 54-698 MHz) have not been fully utilized. To redress the imbalance between congested unlicensed spectrum and underutilized licensed spectrum, the concept of opportunistic spectrum access (OSA) has been proposed. In OSA, primary users (a.k.a. incumbent users) and secondary users are usually co-located and share the same swaths of spectrum. The fallow spectrum that is not occupied by primary users is called "white spaces", and can be opportunistically utilized by secondary users. To achieve this, we need to solve two spectrum sharing problems: (i) primary-secondary incumbent protection, i.e., prevention of harmful interference from secondary users to primary users; (ii) secondary-secondary network coexistence, i.e., mitigation of mutual interference among secondary users. The first problem has been addressed by spectrum sensing techniques in cognitive radio (CR) networks and geolocation database services in database-driven spectrum sharing. A reconfigurable CR can dynamically identify white spaces through various incumbent detection techniques and adjust its operating parameters following the changes in spectrum availability in order to ensure incumbent protection. However, only relying on CRs for sensing-based OSA is not sufficient to achieve reliable protection of incumbents and efficient utilization of white spaces, since spectrum sensing techniques are either ineffective or expensive for the discovery of low-power or passive primary users. For this reason, the use of incumbent geolocation databases for database-driven OSA has found favor with the spectrum regulators and the wireless industry. A geolocation database has access to the detailed operating information of primary users, such as service types, channel reservations, and protection requirements. Based on the up-to-date incumbent characteristics, the database is able to make use of radio wave propagation models to compute location-specific spectrum availability. A secondary user can directly query the database and retrieve the information regarding available white spaces at a given location. In both the sensing-based and database-driven OSA, the second problem for shared spectrum access has received little attention in the literature, and thus is the main focus of this project.

The problems of secondary-secondary coexistence in OSA mainly deal with the mitigation of mutual interference among co-located secondary networks. Interference mitigation mechanisms are usually in the physical (PHY) or media access control (MAC) layers of a wireless network system. In the PHY layer, a variety of techniques can be used to suppress harmful interference, such as interference cancellation, smart antennas, and transmit power control. However, these PHY-layer techniques are not sufficient to effectively maximize spectrum utilization. In the MAC layer, coexisting networks can operate in separate channels (in the frequency domain) or time slots (in the time domain), or at different locations (in the space domain). In this project, resource allocation problems in the MAC layer are addressed, which directly determine whether white spaces can be efficiently utilized.

More details can be found in my Ph.D. dissertation titled "Coexistence of Wireless Networks for Shared Spectrum Access" (Virginia Tech, 2014). 



