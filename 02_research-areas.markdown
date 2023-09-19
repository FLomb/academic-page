---
layout: page
title: Research areas
permalink: /research-outputs/
order: 2
---

A list of my publications is accessible via [Google Scholar](https://scholar.google.com/citations?user=6DhK95QAAAAJ&hl=en) or [ORCiD](https://orcid.org/0000-0002-7624-5886). Some additional items, such as posters presented at conferences, are available from [ResearchGate](https://www.researchgate.net/profile/Francesco-Lombardi-5/research).

Below is an overview of the (primary) research areas I am currently working on. If you have great ideas for collaboration or a thesis on these topics, get in touch!

<div style="background-color: #EAEAEA; text-align:left; vertical-align: middle; padding:20px 20px;">
<p><h style="color: #4032F9;"><b>Algorithms to generate energy system design alternatives.</b></h> 

<img src="/assets/spores.svg" width="100" align="left" style="padding-top: 10px; padding-bottom: 10px" class="next-to-text"/>

Energy system models are tools to support deliberation about which technologies do deploy, and where, to achieve the energy transition. Ideally, they identify for us the 'optimal' answer to such questions. Except, such an optimal answer is often not viable nor desirable in practice. So, is there no alternative? </p>

<p>In fact, there are many technically-feasible, economically-comparable alternatives. They are just normally hidden from view. That's why I work on optimisation methods that make these options available. An example is the <b>SPORES</b> algorithm. By bringing such options to the surface, I aim to expand the perception of what is possible, thereby supporting a more meaningful societal deliberation. Many of the <a href="/projects">projects</a> that fund my current research are based on SPORES. Check out the full paper published in  <a href="https://www.cell.com/joule/fulltext/S2542-4351(20)30348-2?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS2542435120303482%3Fshowall%3Dtrue">Joule</a>.</p>

</div>

<div style="background-color: #F5F5F5; text-align:left; vertical-align: middle; padding:20px 20px;"></div>

<div style="background-color: #EAEAEA; text-align:left; vertical-align: middle; padding:20px 20px;">
<p><h style="color: #4032F9;"><b>Stochastic simulation of user behaviour and demand.</b></h> 

<img src="/assets/demand_sim.svg" width="100" align="left" style="padding-top: 10px; padding-bottom: 10px" class="next-to-text"/>

Energy demand time series are among the most critical inputs for designing carbon-neutral energy systems. However, they are highly uncertain, especially within systems in transition: historical demand data are a poor predictor of future demand, and, often, temporally-resolved metered data simply do not exist, such as when modelling systems in remote areas or when looking at future electric-vehicle fleets. </p>

<p><b>RAMP</b> is an open-source software I designed for the stochastic generation of any user-driven energy demand time series based on few simple inputs. It allows simulating user behaviour, from individual to thousands or millions of users, and understanding temporal demand dynamics at any scale. The RAMP-mobility application of the software is the newest: it generates 1-min <a href="https://www.sciencedirect.com/science/article/pii/S0306261922001416">aggregate mobility and charging profiles across all of Europe</a> based solely on openly-available, easy-to gather data. Check out the project's <a href="https://rampdemand.org">website</a> and <a href="https://github.com/RAMP-project">GitHub</a> repository.</p>

</div>

<div style="background-color: #F5F5F5; text-align:left; vertical-align: middle; padding:20px 20px;"></div>

<div style="background-color: #EAEAEA; text-align:left; vertical-align: middle; padding:20px 20px;">
<p><h style="color: #4032F9;"><b>Scale-adaptable energy system modelling methods and tools.</b></h> 

<img src="/assets/cross_scale.svg" width="100" align="left" style="padding-top: 10px; padding-bottom: 10px" class="next-to-text"/>

Energy transition questions intersect many geographical scales, from households to urban, regional and national levels. When modelling at the scale of a city or larger, technical details within the system end up being overlooked for computational tractability or smoothed out by aggregation. At the same time, energy planning decisions outside the system are ignored despite their potentially high impact on the system design space.</p> 

<p>With my contributions to the multi-scale open-source energy modelling framework <a href="https://callio.pe">Calliope</a>, I provide approaches to: i) translate those essential small-scale technical details for a given research question into information that larger-scale models can handle; and ii) integrate information on the many possible planning decisions outside the system in the uncertainty analysis of the design space. This is what I am doing, for instance, in the <a href="/projects">WindSPORES project</a>. </p>

</div>