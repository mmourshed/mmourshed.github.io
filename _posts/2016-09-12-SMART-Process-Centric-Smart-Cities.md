---
layout:      post
comments:    true
title:       "SMART: A process-oriented methodology for resilient smart cities"
author:      Monjur Mourshed
image:       SMART.png
categories:  news
tags:        [Smart cities theory, SMART]
summary:     "What process should be followed to maximise the utility of smart cities applications?"
---

![Figure]({{ site.url }}/assets/SMART.png)

The inference of insights from big data in smart cities and the subsequent integration with the existing and emerging processes are as important as the development of a smart application itself. Product or goal oriented smart cities approaches often result in siloed applications and miss out on the opportunity to maximise value and the return on investment. We developed a process-oriented framework for smart cities applications called, SMART, comprising five key steps: specify, monitor, analyse, resolve and transform. The development of the framework is based on a review of the state-of-the-art on smart cities approaches and policies in UK and Europe, as well as an analysis of the modelling and architectural requirements for resilient buidings. The work has been presented at the 2016 IEEE International Conference on Smart Cities (ISC2). 

## Background

Activities in _smart_ cities have intensified over the past few years, primarily on the back of significant developments in internet of things (IoT), low-power communication and computing, distributed sensing and monitoring, big-data mining, increased availability of data, and emerging policies on shared and circular economy. Yet, most definitions and existing research attempt to explain smart cities from a product-centric, technological viewpoint that often ignores users and processes, which can be attributed to the lack of consensus on the theory of smart cities; i.e. the questions, why, what and how.

{% include image.html name="SMART-Comparison.png" caption="Mapping between smart city approaches. (a) European Commission’s smart and sustainable cities framework, (b) The proposed DICES framework for conceptualizing smart cities, and (c) Key aspects of a smart city as identified by the UK Government." %}


The application-oriented understanding of smart city technologies has discipline-specific bias, often resulting in the lack of interoperability between isolated systems. The evident drawback of siloed applications is that their true potential is seldom realised because of the lack of integration, which also prevents the consideration of interdependent relationships---both existing and evolving. For example, an intelligent transport system (ITS) that aggregates and fuses in-vehicle data from users with monitored traffic and infrastructure data to provide real-time support for reducing journey time, congestion and fuel use, is a _smart mobility_ solution. On the other hand, the optimal management and dispatching of energy infrastructure assets considering intermittent generations from distributed energy resources (DER) and consumer behavior against dynamic pricing is a _smart energy_ application. Both applications can be implemented on their own but if conceived in an integrated way, the smart energy solution could consider the interdependent effects of electric vehicles (EV) with the electricity grid, as well the use of EV for storing excess generation from DERs, with potential for reducing peak demand for energy---a demand-side management (DSM) strategy. 

## SMART: A process-oriented theory

We propose a process-oriented methodology conveniently termed, SMART, involving five steps: specify, monitor, analyze, resolve and transform. We consider **monitoring** to be the central task in smart cities. In this context, monitoring is a cyclic process and applies to both the existing and future data infrastructure. It is cyclic in the sense that we continue to update the monitoring (i.e. data) infrastructure by learning from experiences. The remainder of the SMART methodology builds on monitored data and comprises the following process elements: 

* **Specify**. Citizen-centric, sustainable goals and objectives are specified considering the multi- and interdisciplinary nature of interactions between application sectors. Specifications are often based on an analysis of the previously or existing monitored data;

* **Analyze**. Success in a data-centric process relies on the ability to glean insights and intelligence from the underlying dataset. This step in the SMART methodology relies on computational, statistical and empirical modeling techniques for inferring insights, some or all of which can be automated to eliminate or reduce obsolescence; 

* **Resolve**. Solution space in a smart city is often multi-dimensional and decisions are multi-objective. Computational and operational research (OR) techniques are often best suited for multi-dimensional search for optimal decisions. Resolve aims to enable evidence-based decisions from insights gathered in the previous step, analyze; however, resolve has feedback loop with specify and analyze, which can be taken if necessary; and

* **Transform**. Relates to the implementation of the optimal decisions taken at the earlier step and focuses on standards-based evolution of the physical infrastructure so that adaptability and resilience of the smart city are not compromised. 

## Conclusion

We implemented the SMART methodology for developing a risk- and evidence-based platform for resilient and optimal design of buildings. The concept of domain objects is used to enable adaptability of the software architecture and services.

### Citation
> Mourshed M, Bucchiarone A, Khandokar F (2016) SMART: A process-oriented methodology for resilient smart cities, In: _Second IEEE International Smart Cities Conference (ISC2 2016)_, Trento, Italy, 12–15 September, pp. 775–780. [Download preprint](http://orca.cf.ac.uk/93361/1/1570281398.pdf). DOI: [10.1109/ISC2.2016.7580872](http://dx.doi.org/10.1109/ISC2.2016.7580872).

