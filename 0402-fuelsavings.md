Brief: Think about what the final formula could look like \
Date: 04/02/2026

### Notes

Today I looked into the fuel savings part of the core cash flow equation.

**Core equation**

$$
\text{CF} = \text{fuel savings} + \text{carbon savings} - \text{service cost}
$$    


**Variables**

| Symbol | Variable | Measurement Unit |
| :--- | :--- | :--- |
| $M$ | Fuel cost | Currency/Year |
| $S$ | Fuel savings | Currency/Year |
| $P$ | Fuel price | Currency/Metric tonnes |
| $A$ | Amount of fuel used | Metric tonnes/Year |
| $C$ | Average Fuel consumption | Metric tonnes/Day |
| $t$ | Operating days | days/Year |


## Model 1 - helpful for calculating cash flows per year (deliverable 1.3)

**Fuel Cost**

$$
M = P \times A
$$
$$
M = P \times C\times t
$$

**Fuel Savings**

$$
S = M_1 - M_2
$$
$$
S = P \times (C_1 - C_2) \times t
$$

e.g $C_1$ is no hull cleaning, $C_2$ is ScrubMarine cleaning

## Model 2 - better for unit analysis by fuel, type, size, route, operating conditions (deliverable 1.1 and 1.4)

$$
M = P \times A
$$

where 

$$
A = f(\text{fuel, type, size, route, operating conditions})
$$

Some of the resources below will be useful for determining $f$.

### New knowledge

* Ship fuel consumption is usually measured in metric tonnes per day
* Common types of fuel
    * Heavy Fuel Oil (HFO) : accounts for 80% of cargo ships (martimepage.com), cheap but high polutants
    * Marine Gas Oil (MGO) : more expensive but fewer emmissions, good in places where
    emissions are expensive such as ECAs in North America
    * Others: Liquefied Natural Gas (LNG), Biodiesel, Hydrogen, Methane
* Vessel Operation Profile - speed through water, engine load factors, transit time, and time spent maneuvering or at berth (https://energy.sustainability-directory.com/area/vessel-operational-profiles/)


### Helpful Resources

* https://www.balticexchange.com/en/who-we-are/guide-to-modern-shipping/main-vessel-types.html: vessel types
* https://www.imo.org/en/ourwork/environment/pages/data-collection-system.aspx: fuel consumption
* https://mrv.emsa.europa.eu/#public/eumrv: emmissions
* https://maritimepage.com/ship-fuel-consumption-per-mile-or-how-much-fuel-does-a-cargo-ship-use/: fuel types & consumption


### Questions for client

* Why are they asking us to do this?
* What is more important: unit analysis on a single route/operating condition or cash flow analysis (yearly)?


### Next steps

Actions:
* Find a solution for $f$ = $\text{amount of fuel used}$ given conditions
* Determine carbon savings part of the core equation

