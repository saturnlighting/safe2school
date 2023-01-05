
<!-- README.md is generated from README.Rmd. Please edit that file -->

# safe2school

<!-- badges: start -->
<!-- badges: end -->

The goal of safe2school is to form a basis for reproducible analysis of
open data to estimate current levels of, and estimates of future
potential for, active travel to schools, anywhere in the world, down to
the street level. The motivation is well documented: active travel is an
effective solution to environmental, health and social issues.
Specifically, there is a crisis of sedentary lifestyles affecting young
people worldwide. Building active travel into everyday life can mitigate
this crisis and lead to better mental health and educational outcomes,
and tackle inequalities that are exacerbated by the transport system.

By active travel we mean school pupils ‘moving on their own steam’ by
one of the following modes of transport:

- Walking
- Wheeling, which can include scooting, rollerblading, or even
  skatingboarding
- Biking, using a pedal cycle
- Ebiking, using a pedal cycle with electric assist (aka pedelec)

There is a substantial body of research on active travel among young
people and ‘safe routes to school’ in particular. However, the relevance
of much of research for local transport planners tasked with
prioritising interventions in specific locations is limited because
results are rarely provided at the street level at which local
infrastructure decisions, such as improving sidewalks or creating new
protected cycles, are made.

One approach that does provide local results, and which is used by
transport planners in cities across England, is the Propensity to Cycle
Tool (PCT). First developed in 2015, the approach was extended in 2018
to estimate cycling potential to schools across England Goodman et al.
(2019). The results are publicly available nationwide via an interactive
web application hosted at [www.pct.bike](https://www.pct.bike/), as
shown in the image below for London, UK.

![](images/image-1448227588.png)

Problems associated with the ‘PCT approach’ represented in the image
above include:

- It is very focussed on data from one place, England, and is therefore
  not easily applicable to other countries or cities worldwide.

- It relies on origin-destination data *with estimates of mode split per
  OD pair,* something that is unfortunately not available in most
  places; mode of travel to school is rarely recorded and is seldom
  available at the OD level when it is.

- Furthermore, in many cases OD data representing travel to school is
  not available at all.

In many cases, especially in contexts where local or national
governments are undertaking research to support effective interventions,
OD datasets are available but these cannot be shared. This makes any
derived outputs subject to the same potentially strict licensing
agreements that apply to the OD data, preventing the data from being
used by a broad range of stakeholders including parents, head teachers,
advocacy groups and consultancies. Yet making the results of transport
models open is key to their impact Lovelace, Parkin, and Cohen (2020).

# References

<div id="refs" class="references csl-bib-body hanging-indent">

<div id="ref-goodman_scenarios_2019" class="csl-entry">

Goodman, Anna, Ilan Fridman Rojas, James Woodcock, Rachel Aldred,
Nikolai Berkoff, Malcolm Morgan, Ali Abbas, and Robin Lovelace. 2019.
“Scenarios of Cycling to School in England, and Associated Health and
Carbon Impacts: Application of the ‘Propensity to Cycle Tool’.” *Journal
of Transport & Health* 12 (March): 263–78.
<https://doi.org/10.1016/j.jth.2019.01.008>.

</div>

<div id="ref-lovelace_open_2020" class="csl-entry">

Lovelace, Robin, John Parkin, and Tom Cohen. 2020. “Open Access
Transport Models: A Leverage Point in Sustainable Transport Planning.”
*Transport Policy* 97 (October): 47–54.
<https://doi.org/10.1016/j.tranpol.2020.06.015>.

</div>

</div>
