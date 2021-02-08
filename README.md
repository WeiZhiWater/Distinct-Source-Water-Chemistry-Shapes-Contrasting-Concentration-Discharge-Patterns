## Distinct-Source-Water-Chemistry-Shapes-Contrasting-Concentration-Discharge-Patterns

**Zhi, W.**, Li, L., Dong, W., Brown, W., Kaye, J., Steefel, C., & Williams, K. H. (2019). Distinct source water chemistry shapes contrasting concentration‐discharge patterns. *Water Resources Research*, 55(5), 4233-4251. [doi: 10.1029/2018WR024257](https://doi.org/10.1029/2018WR024257)

<br/>

## Abstract
- Contrasting concentration‐discharge (C‐Q) relationships have been observed widely, yet a mechanistic framework that can interpret diverse patterns remains elusive. 
- This work hypothesizes that seemingly disparate C‐Q patterns are driven by switching dominance of end‐member source waters and their chemical contrasts arising from subsurface biogeochemical heterogeneity. 
- We use data from [Coal Creek](https://www.coalcreek.org/), a high‐elevation mountainous catchment in Colorado, and a tributary of the [East River](https://watershed.lbl.gov/), and a recently developed watershed reactive transport model ([BioRT‐Flux‐PIHM](https://github.com/PSUmodeling/BioRT-Flux-PIHM)). Sensitivity analysis and Monte‐Carlo simulations (500 cases) show that reaction kinetics and thermodynamics and distribution of source materials across depths govern the chemistry gradients of shallow soil water and deeper groundwater entering the stream. 
- A general equation regulates the power law slopes (b) of C‐Q patterns. The equation quantitatively interprets b values of 11 solutes (dissolved organic carbon, dissolved P, NO3−, K, Si, Ca, Mg, Na, Al, Mn, and Fe) from three catchments ([Coal Creek](https://www.coalcreek.org/), [Shale Hills](https://czo-archive.criticalzone.org/shale-hills/), and [Plynlimon](https://www.ceh.ac.uk/our-science/monitoring-site/plynlimon-critical-zone-observatory)) of differing climate, geologic, and land cover conditions. 

<br/>

## Figures
- Study site of Coal Creek watershed, CO
- Watershed-scale biogeochemical reactive transport model: [BioRT‐Flux‐PIHM](https://github.com/PSUmodeling/BioRT-Flux-PIHM)
- Concentration‐discharge slope b as a function of concentration ratio

### Coal Creek watershed
Coal Creek is a headwater high‐elevation (2700 - 3700 m) catchment in the central Rocky Mountains of Colorado, USA. It is a third‐order stream in Gunnison County and drains an area of approximately 53 km2 about 200‐km southwest of Denver. The mean annual temperature is around 0.9 °C. The watershed is seasonally snow‐covered from approximately
mid‐November to mid‐June with a maximum ground snowpack of >150 cm typically in mid‐February, after which the snowmelt dominates. The watershed consists primarily of
evergreen forest (65%) and herbaceous vegetation (20%), followed by deciduous forest (9%), barren land (3%), and woody wetland (3%). The lithology includes primarily sandstone (39%) and mudstone (15%; Figure 1a) that belong to the Mesaverde, Tertiary Wasatch, and Ohio Creek Formations (Manning et al., 2008; Streufert, 1999). Plutonic rock (36%) originated during the Middle Tertiary, when the Red Lady stock was emplaced under Mt Emmons and widespread volcanism occurred south of the study area. A small area (10%) in the valley is covered by Quaternary Glacial Drift, which consists of various surficial deposits including unsorted glacial till and associated sand and gravel deposits.

<p align="center">
  <img src="/figures/figure1.jpg" alt="Study site: Coal Creek Watershed" width="600">
</p>

### BioRT-Flux-PIHM: A Watershed Biogeochemical Reactive Transport Model
The model couples three modules: a multicomponent reactive transport module BioRT, the land‐surface interaction module Flux for processes such as solar radiation and
evapotranspiration (ET), and the surface hydrology module PIHM for hydrological processes (e.g., precipitation, infiltration, recharge, surface runoff, and subsurface flow). The BioRT module takes in the computed water fluxes and storage from Flux‐PIHM and simulates processes including advection, diffusion, dispersion, and biogeochemical reactions and outputs aqueous and solid concentrations. The reactions can be kinetics‐controlled (mineral dissolution and precipitation and microbe‐mediated reactions) and thermodynamically
controlled (e.g., ion exchange, surface complexation or sorption, and aqueous complexation). Flux‐ PIHM solves for water‐related variables including water storage, flow, soil moisture, and water table depth. For subsurface flow, the model distinguishes between active interflow in shallow soil zones and groundwater flow that is relatively shallow and is connected to the stream but is deeper than soil

<p align="center">
  <img src="/figures/figure2.jpg" alt="Watershed model: BioRT-Flux-PIHM" width="600">
</p>

### C‐Q slopes as a function of subsurface concentration contrast
Flushing patterns (b > 0.1) cluster toward the upper left with high soil water concentrations (Csw) relative to groundwater concentrations (Cgw). In contrast, dilution (b < −0.1) occurs toward the bottom right with high Cgw relative to Csw. Chemostasis shows up close to the 1:1 line, as long as the soil and groundwater concentrations are similar with a concentration ratio (Cratio = Csw/Cgw) between 0.6 and 1.8. The figure also shows C‐Q slope b and Cratio values compiled from two other catchments: Shale Hills in
Pennsylvania and Plynlimon in Wales, UK. In general, we see that data points follow the curve defined by the equation, although the range of b values may vary for different catchments and solutes.

<p align="center">
  <img src="/figures/figure11.jpg" alt="C-Q pattern as a function of concentration contrast" width="600">
</p>
