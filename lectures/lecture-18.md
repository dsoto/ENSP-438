## ENSP 202, Lecture 18
### Professor Daniel Soto, Sonoma State University
### Thursday, 13 Mar 2014

## Topics
- Battery Parameters
- Battery LCOE
- Off-grid sizing example

## Assigned
[Upcoming Assignments](https://github.com/dsoto/ENSP-438/blob/master/schedule/upcoming.md)

<!--
solar city followup
-->

## Due
- Read REEPS2 7.1 -- 7.5

## Project
- List of peer reviewers on Moodle

## Off-grid vs on-grid
- Grid Backup for on-grid
- Battery or generator backup for off-grid
- Blackouts are possible in off-grid designs

## Off-grid efficiencies
![](../figures/REEPS2CH6-off-grid-efficiencies.pdf)

- Additional energy loss is introduced by the battery storage

## Off-grid battery bank
![](../figures/off-grid-battery-bank-gil.pdf)

## Battery figures
- Capacity in amp-hours
- Voltage
- Cycle life
- Charge/Discharge Efficiency
- Calendar life
- Cost per kWh
- Allowable depth of discharge


## Battery Specifications
[Wiki Battery Specs](http://en.wikipedia.org/wiki/Rechargeable_battery)

## Charging and discharging rates
- C rate
- Useful to think of as a current
- C/5 is the current that will deplete or charge the battery in 5 hours
- Charging or discharging at high C rates is usually less efficient

## Depth of discharge
- Depth of discharge is the percentage of a battery's capacity that is
  consumed before recharge
- Lead acid batteries have shorter cycle life if used at a higher depth
  of discharge

## Energy Density
![](../figures/REEPS2CH6-energy-density.pdf)

Lead acid weighs more for every kilowatt-hour stored, but this doesn't
matter for stationary applications.

## Series and Parallel combinations of batteries
![](../figures/REEPS2CH6-battery-series-parallel.pdf)

## Adding batteries
- Series
- Parallel
- Written

## Lead acid reaction
![](../figures/REEPS2CH6-lead-acid.pdf)

- Hydrogen gas can be created causing an explosion hazard
- Over time Lead Sulfate builds up on plates, lowering capacity

## Battery capacity in cold weather
![](../figures/REEPS2CH6-battery-cold-capacity.pdf)

Cold temperatures cause a reduction in the battery capacity.

## Reliability Increases Cost

![](../figures/Lee-cost-vs-esp.pdf)

- Lee, Soto, Modi, In Press, Renewable Energy

## Battery as power plant
![](../figures/battery-tikz.pdf)


## Levelized cost of electricity (LCOE)
- Fixed costs
    - Do not change with amount of electricity sold
- Variable costs
    - Are proportional to amount of electricity sold

## LCOE

$$ \textrm{LCOE (\$/kWh)}
   = \frac{\textrm{Annual fixed cost} +
           \textrm{Annual variable cost}}
          {\textrm{Annual electricity output}} $$

## Levelized Cost of Battery Energy
- Spreadsheet


