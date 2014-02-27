## ENSP 202, Lecture 11
### Professor Daniel Soto, Sonoma State University
### Tuesday, 18 Feb 2014 (Week 6)

## Topics
- REEPS2 5.5 -- 5.9
- Combinations of cells, modules, arrays
- Temperature effects

## Assigned
- Homework 2 Due Thursday
- Quiz possible at any time

## Due
- Nothing

## News
- [Utility PV Cost](http://www.solarserver.com/solar-magazine/solar-news/current/2014/kw07/us-doe-us-utility-scale-solar-pv-more-than-60-to-cost-competitiveness-goal.html)
- Internships

## Questions
- How do modules combine in series and parallel?
- Can we add their powers?
- What happens when modules aren't identical?
- How do modules behave when they are hot or cold?

## Review: IV Curves
- Is a solar panel more like an ideal voltage or current source?

## Review: Short circuit, open circuit
![](../figures/REEPS2CH5-PV-open-circuit-short-circuit.pdf)

## Maximum power point MPP
![](../figures/REEPS2CH5-MPP.pdf)

<!--
- which point is short circuit?
- which point is open circuit?
-->

## Solar module
- Several pn junctions
- Usually wired in series

## Cells, Modules, Arrays
- Several modules
- Wired in series, parallel, or combination
- figure 5.35 -- 5.39

## Cells, Modules, Arrays
![](../figures/REEPS2CH5-cell-module-array.pdf)



## PV in series
- How do the curves stack?
- In series, voltages add
- Currents must be matched

## Cells in series
![](../figures/REEPS2CH5-curve.pdf)

## Modules in series
![](../figures/REEPS2CH5-module-series.pdf)

<!--
use simplified module curve and stack
-->


## Modules in parallel
- How do the curves stack?
- In parallel, currents add

<!--
use simplified module curve and stack
-->


##
![](../figures/REEPS2CH5-module-parallel.pdf)

##
![](../figures/REEPS2CH5-module-series-parallel.pdf)

##
![](../figures/REEPS2CH5-PV-full-sun.pdf)

## Variation of curves with temp and insolation

## Variation in temperature and insolation
![](../figures/REEPS2CH5-PV-temperature-illumination.pdf)

## Standard test conditions
- These are the laboratory conditions for manufacturer testing
- 1 kW/m$^2$ insolation
- Spectral distribution corresponding to AM 1.5
- Cell temperature of 25C
- The reported power must be adjusted to account for real-world
  conditions

## PV specifications
![](../figures/REEPS2CH5-PV-specifications.pdf)

## Temperature effects
- Normal operating cell temperature (NOCT)
- Expected temperature at
    - 20C air temperature
    - 0.8 kW/$m^2$ insolation (0.8 sun)
    - 1m/s wind
- For most modules this is about 45C

## Temperature

- We can predict the cell temperature (REEPS2 Eq. 5.23)

$$ T_{cell} = T_{amb} + \frac{NOCT - 20C}{0.8}S $$

- If it is hot, the cell temperature rises linearly
- If it is sunny, the cell temperature rises linearly
- News flash: stuff in the sun gets hot

<!--
this tells you what you already know
stuff in the sun gets hot
cars in the sun get hot
-->


## Temperature Coefficient of Max Power

- We can predict the maximum power based on the cell temperature

$$ P_{max} = P_{STC} \cdot (1 - \textrm{temp coeff} \cdot (T_{cell} - T_{STC})) $$

- $P_{STC}$ power measure in lab under standard test conditions (STC)
- $T_{STC}$ cell temperature in lab under STC (25C)
- temperature coefficient is the temperature coefficient of $P_{max}$
  %/C


## Shading/mismatch
- We use the equivalent circuit model that includes resistances to show
  these effects
- These resistances dissipate power and reduce the output power

## Shading
- To mitigate shading issues at the cell level we use bypass diodes
- To mitigate shading issues at the module level we use microinverters

