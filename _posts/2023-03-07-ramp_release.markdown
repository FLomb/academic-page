---
layout: post
title:  "First multi-institution release of RAMP"
date:   2023-03-07 18:00:00 +0100
categories: jekyll update
---

A new, next-generation release of the [RAMP software](/assets/lectures/RAMP_project_and_RAMP_mobility.pdf) is out alongside a new website ([rampdemand.org](https://rampdemand.org))!

But what is RAMP? It is an **open-source software suite** that capitalises on uncertainty through a **stochastic algorithm**, relying on a few simple inputs to simulate any user-driven **energy demand time series** at high resolution. Since its first release in April 2019 with a focus on [off-grid energy system design](edu.nl/6b8gx), RAMP has been reused by several institutions, including Reiner Lemoine Institut, ETH Zürich, Eurac Research, VITO, TU Delft and many others. It was also soon clear that the underlying stochastic algorithm had broad potential beyond off-grid areas and could provide synthetic data wherever metered data does not exist. For instance, when looking at mobility and charging load profiles of future [electric-vehicle fleets](edu.nl/q7ft7).

<img src="/assets/vehicles.gif" align="center"/>

Born as a small side project, RAMP is now a **multi-institution software development effort**. Since June 2022, Reiner Lemoine Institut, VITO and the University of Liège have joined forces with TU Delft to co-fund the development of the 'next-gen' version of RAMP. Now, we have finally released the first such **next-gen version** of RAMP as [v0.4.0](https://github.com/RAMP-project/RAMP/tree/v0.4.0): more user-friendly and efficient, installable via pip, and more extensively documented. Our next step: reconnecting the standalone RAMP-mobility application to this next-gen development process, making it an optional plug-and-play application of the base software. 

Want to help? Check out RAMP's [website](https://rampdemand.org) and find out how to contribute!