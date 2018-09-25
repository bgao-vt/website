+++
# Date this page was created.
date = "2016-04-01"

# Project title.
title = "Database-Driven Dynamic Spectrum Sharing"

# Project summary to display on homepage.
summary = "To define dynamic, multi-tier incumbent exclusion zones"

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "dbss.jpg"

# Optional image to display on project detail page (relative to `static/img/` folder).
image = ""

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["dynamic spectrum access","geolocation database","spectrum sharing"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

+++

In database-driven dynamic spectrum sharing, each secondary user (SU) queries a geolocation database to identify fallow spectrum that is not being occupied by incumbent users (IUs). Fallow spectrum in TV bands is often referred to as "white spaces", but we will use this term in this paper to denote fallow spectrum in arbitrary bands. A licensed channel serves as a white space channel for the requesting SU only if the SU is not located in the exclusion zones (EZs) for IUs operating on this channel. Hence, the accessible area outside the EZs, which is the service coverage of this channel as a white space channel, is directly determined by the regulation of EZs. The boundary of a legacy EZ is static, and it is calculated by the database based on incumbent registrations and operating characteristics, interference protection requirements, and numerical results from signal propagation models. The static regulation of an EZ is defined in such a way that the IUs are protected from the union of all possible interference scenarios, and thus can easily result in a worst-case, conservative solution for incumbent protection. However, overly-conservative EZs cause high probability of false alarms (i.e., erroneous detection of IUs when they are absent) to keep low probability of false dismissals (i.e., missed detection of IUs when they are present), and thus secondary spectrum access opportunities have to be unnecessarily wasted. For example, the static EZs estimated in a NTIA report to protect radars in 3.5 GHz band preclude approximately 60% of the U.S. population from accessing fallow spectrum, which would severely undermine the economic incentive for realizing spectrum sharing.

Generally, the boundaries of legacy EZs can be refined by adding additional details to a conventional propagation model. We aim to reduce the probability of false alarms by considering static terrain data or average aggregate interference to IUs as the additional details. Furthermore, due to the dynamic nature of spectrum sharing, incorporating real-time information on spectrum availability is much more effective in lowering the probability of false alarms. In fact, the information gathered from spectrum sensing offers what a geolocation database lacks---real-time identification of spectrum access opportunities that would have been overlooked otherwise. The FCC has accepted the use of spectrum sensing to define smaller EZs in 3.5 GHz band. In particular, spectrum sensing is invaluable in understanding the interference environment when constructing an accurate propagation model is infeasible, e.g., in indoor environments. Hence, we also focus on the concept of dynamic, multi-tier EZs that incorporates participatory spectrum sensing carried out by SUs into geolocation database. We aim to propose a dynamic zoning framework, which answers why, where, and how spectrum sensing is incentivized.


