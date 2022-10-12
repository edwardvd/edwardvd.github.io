(ch:effluentsuspendedsolids)=
# Effluent suspended solids
_Parts of this chapter have been published in Water Research _147_, 50-59 (2018) {cite:p}`VanDijk2018`._
## Abstract
The main processes contributing to elevated effluent suspended solids in the full-scale aerobic granular sludge process were studied. The two most important processes were (1) rising of sludge due to degasification of nitrogen gas (produced by denitrification) and (2) wash-out of particles that intrinsically do not settle such as certain fats and foams. A mathematical model was made to describe the process of degasification of nitrogen gas during the feeding phase in an AGS reactor. The process of rising sludge due to degasification could be limited by stripping out the nitrogen gas before starting the settling phase in the process cycle. The wash-out of scum particles could be reduced by introducing a vertical scum baffle in front of the effluent weir, similar to weirs in traditional clarifiers. The {term}`PNU<PNU>` was operated with a nitrogen stripping phase and scum baffles for 9 months at an average biomass concentration of 10 g&nbsp;L<sup>-1</sup> and an average granulation grade of 84&hairsp;%. In this period the influent suspended solids concentration was 230&hairsp;&#177;&hairsp;118 mg&nbsp;L<sup>-1</sup>, while the concentration of effluent suspended solids was 7.8&hairsp;&#177;&hairsp;3.8 mg&nbsp;L<sup>-1</sup>.


## Introduction
```{figure} figures/chapter-2/degasification_abstract.svg
---
name: fig:graphical_abstract_ch2
---
Graphical abstract.
```

If we look at the effluent quality of full-scale {term}`AGS<AGS>` reactors reported in literature, low effluent values for COD, total nitrogen and total phosphorus can be easily met, but average suspended solids effluent concentrations are relatively high with a range of 5&hairsp;-&hairsp;20&nbsp;mg&nbsp;L<sup>-1</sup> (see {numref}`tab:reportedsuspendedsolids`).
```{margin}
<sup>1</sup>: summer/winter<BR/>
<sup>2</sup>: {cite:p}`VanDerRoest2011`<BR/>
<sup>3</sup>: {cite:p}`Giesen`<BR/>
<sup>4</sup>: {cite:p}`Pronk2015`<BR/>
<sup>5</sup>: {cite:p}`Giesen2016` 
```
```{table} Reported effluent concentrations for different Nereda<sup>&#174;</sup> plants.
:name: tab:reportedsuspendedsolids

| Plant        |   COD                         |   N<sub>tot</sub>-N                            |   NH<sub>4</sub>-N                  |   NO<sub>3</sub>-N                  |   P<sub>tot</sub>-P                            |   PO<sub>4</sub>-P               |   SS                            |     
| --- | --- | --- | --- | --- | --- | --- | --- | 
|  | mg&nbsp;L<sup>-1</sup>   | mg&nbsp;L<sup>-1</sup>   | mg&nbsp;L<sup>-1</sup>   | mg&nbsp;L<sup>-1</sup>   | mg&nbsp;L<sup>-1</sup>   | mg&nbsp;L<sup>-1</sup>   | mg&nbsp;L<sup>-1</sup>   |    | 
Epe<sup>2</sup>           |                                 |                                 |   0.5                           |   4                             |                                 |   0.5                           |   10-20                         |   
Dinxperlo<sup>2</sup>    |                                 |                                 |   0.2                           |   5                             |                                 |   2                             |   15-20                         |   
Gansbaai<sup>3</sup>     |   40                            |   <10                           |   <1                            |                                 |   3.2                           |                                 |   $<$5                          |   
Garmerwolde<sup>4</sup>  |   64                            |   6.9                           |   1.1                           |                                 |   0.9                           |   0.4                           |   20                            |    
Ryki<sup>5</sup>         |   45                            |   5.60                          |                                 |                                 |   0.85                          |                                 |   13                            |    
Vroomshoop<sup>5</sup>   |   55                            |   7.2                           |   1.4/3.0<sup>1<sup>    |   2.0                           |   0.9                           |   0.6                           |   10                            |    
```


Some reports indicate an increase in effluent suspended solids concentrations for AGS reactors  with increasing granulation {cite:p}`Li2008, Rocktaschel2015`. In most laboratory studies the focus is on the granulation process and wasting of sludge for ease of operation is combined with decanting of the effluent {cite:p}`DeKreuk2005`. As a result, biomass is present in the effluent of laboratory reactors. This poses no problem under laboratory conditions, but for the full-scale treatment of sewage the removal of suspended solids is an integral part of the purification process and is usually limited by law. Since hydraulics of laboratory and even pilot plant installations are not representative for full-scale conditions, effluent suspended solids can only effectively be studied at full-scale installations. In full-scale applications the effluent and sludge withdrawal are separated processes. This leads to relatively low suspended solids effluent concentrations, certainly when compared to influent values  {cite:p}`Pronk2015`. Still,  the reported average values of 5&hairsp;-&hairsp;30 mg L<sup>-1</sup> are higher than usually reported for conventional activated sludge processes, which can be considerably lower than 10&nbsp;mg&nbsp;L<sup>-1</sup> {cite:p}`SParker`.

Elevated levels of effluent suspended solids have been intensively studied over the last decades in conventional activated sludge systems. Commonly reported issues in these systems are bulking sludge and foam formation {cite:p}`Jenkins1992`. Another reported issue in secondary clarifiers is the rising of sludge due to denitrification {cite:p}`Henze1993`. Denitrification can lead to nitrogen bubble formation (degasification) if over-saturation of nitrogen gas in the liquid is reached. The bubbles attach to the sludge flocs which then rise towards the top of the clarifier and wash out with the effluent.

Sludge settling too fast, indicated by a low sludge volume index (SVI), is also reported to cause elevated levels of suspended solids in the effluent of conventional activated sludge systems, although this effect is doubted by others reporting a strong relation with the flocculator design {cite:p}`SParker, Parker1996, Vitasovic1997`. Since reported SVI values for full-scale AGS reactors are generally low (35&hairsp;-&hairsp;70 mL g<sup>-1</sup>) {cite:p}`Pronk2015,VanDerRoest2011` this might also be a potential cause of elevated levels of effluent suspended solids.

Besides a different sludge morphology and likely flocculation behaviour, current AGS plants according to the Nereda<sup>&#174;</sup> concept deviate also in hydraulics from secondary settling tanks. Secondary clarifiers have typical superficial upflow velocities of 0.5&hairsp;-&hairsp;1.0 m h<sup>-1</sup>, while the complex flow in the clarifier is mainly caused by density currents {cite:p}`Zhou1992`. For the Nereda<sup>&#174;</sup> technology effluent results from pumping influent in the bottom of the granular bed. This generates an upward plug flow in the reactor with typical superficial velocities in the range of 2&hairsp;-&hairsp;5 m h<sup>-1</sup> through a granular bed with on top of that a layer of flocculent sludge. The relatively higher upflow velocities in Nereda<sup>&#174;</sup> reactors might be responsible for the washout of floating sludge and fat-like particles. In contrast to conventional activated sludge systems, the mechanisms behind the formation and control of effluent suspended solids for full-scale aerobic granular sludge reactors are not yet fully understood.

The aim of this study was to evaluate the main processes leading to effluent suspended solids in full-scale AGS reactors, and investigate options to minimize effluent suspended solids. We focused on both removal of floating material and degasification of nitrogen gas. Full-scale experiments were performed in the {term}`PNU<PNU>` and a mathematical model was developed to describe the degasification of nitrogen gas during the operation of the aerobic granular sludge reactor.

## Materials and methods
### Description of the plant
Experiments were done in the \glsdesc{pnu}. The reactor has a footprint of 150 m<sup>2</sup> and a water depth of 7.00 m. The influent pumps have a total capacity of 900 m<sup>3</sup> h<sup>-1</sup>.  The influent is pumped directly from a main sewer line of the Overvecht district in Utrecht. The sewage consists mainly of domestic wastewater. Wastewater characteristics during this study are given in {numref}`tab:influent`. After screening by a 6 mm perforated plate screen, the wastewater is directly pumped into the reactor. During the trial the reactor was operated at a MLSS concentration of 8&hairsp;-&hairsp;12 kg m<sup>-3</sup>, a SVI5 of 34&hairsp;-&hairsp;57&nbsp;mL&nbsp;g<sup>-1</sup> , a SVI30 of 33&hairsp;-&hairsp;43&nbsp;mL&nbsp;g<sup>-1</sup>, a volumetric loading rate of 0.6&hairsp;-&hairsp;2.7&nbsp;m<sup>3</sup>&nbsp;m<sup>-3</sup>&nbsp;d<sup>-1</sup> and an average sludge loading rate of 0.08&nbsp;kg<sub>COD</sub>&nbsp;kg<sub>MLSS</sub>&nbsp;d<sup>-1</sup>. On average 84&hairsp;% of the biomass present in the reactor was granulated during the experimental period (i.e. granule size larger than 0.2&nbsp;mm). Average granule size distributions are shown in {numref}`tab:granules`. The reactor is equipped with two blowers each with a capacity of 400 m<sup>3</sup> h<sup>-1</sup>. Air is supplied to the reactor using micro bubble diffusors evenly distributed on the floor of the tank.

```{table} Influent characteristics of the PNU during the study.
:name: tab:influent
|                  |  Average           |  Min               |  Max               | 
| --- | --- |--- |--- |
|Parameter         |  mg L<sup>-1</sup>  |  mg L<sup>-1</sup>  |  mg L<sup>-1</sup>  |  
|COD               |  707.0             |  442.4             |  1007.5            | 
|N<sub>Kj</sub>     |  64.0              |  35.0              |  81.7              | 
|NH<sub>4</sub>-N      |  46.1              |  25.1              |  58.6              | 
|P<sub>tot</sub>-P  |  8.9               |  5.3               |  11.8              | 
|PO<sub>4</sub>-P     |  5.6               |  3.2               |  8.2               | 
|SS  |  230.0             |  160.0             |  380.0             |  
```

The reactor was operated with a normal Nereda<sup>&#174;</sup> cycle as described in section [Nereda technology](sec:nereda_technology). Process conditions were set to target full biological nitrogen and phosphorus removal. No possibilities for chemical dosing were present in the reactor. During the trial nitrogen removal was established by nitrification and denitrification.

The cycle time varied between 4 and 8 hours, with 1 hour of anaerobic feeding and simultaneous effluent withdrawal, a variable reaction phase and a phase for mixing, settling and decanting of sludge of 30 to 60 minutes.

The reaction phase was stopped when the set points, 2&nbsp;mg&nbsp;L<sup>-1</sup> and 3&nbsp;mg&nbsp;L<sup>-1</sup> for respectively ammonia and nitrate were reached. During the reaction phase the dissolved oxygen concentration was controlled in the range of 
1.0&hairsp;-&hairsp;2.0&nbsp;mg&nbsp;L<sup>-1</sup>.

The plant is in operation since the 1<sup>st</sup> of April 2013.  The reactor was started up without baffles in front of the overflow weir. On the 3rd of June 2015 vertical baffles were placed in front of the effluent weirs, to investigate the effect of scum baffles on the concentration of effluent suspended solids.

### Online measurements
The reactor was equipped with probes for dissolved oxygen, redox potential, water level, temperature, turbidity, and nitrate. Ammonium and phosphate were continuously measured using a filter unit and auto sampling device (Hach Lange; Filtrax, Amtax and Phosphax). The filter unit was situated 0.5 meter below the water surface. Sampling was done at an interval of 5 minutes. A turbidity sensor (Hach Lange; Solitax) was present in the effluent gutter to observe the presence of suspended solids.

### Sampling
Samples for analyses of influent and effluent were collected using refrigerated auto samplers, collecting flow proportional samples for both influent and effluent. Suspended solids concentrations of both influent and effluent were measured by filtering 1&nbsp;L of sample with a glass fiber filter, which was dried at 105&nbsp;&#176;C until no weight change was measured.

Grab samples for {term}`MLSS<MLSS>` analyses were taken from the top of the reactor after at least 15 minutes of aeration at full capacity to ensure sufficiently mixed conditions.

### Physical characteristics of the sludge
To determine the granule size distribution 1&nbsp;L of sample was poured over a series of sieves with different mesh sizes (200&nbsp;&#181;m, 400&nbsp;&#181;m, 630&nbsp;&#181;m, 1000&nbsp;&#181;m and 2000&nbsp;&#181;m). These sieve fractions together with 100&nbsp;mm of unsieved sludge were dried at 105&nbsp;&#176;C. The sludge volume index (SVI) was measured by pouring 1000&nbsp;mm of mixed, undiluted sludge into a graduated measuring cylinder. The sludge volumes were measured after 5 and 30 minutes.

```{table} Average granule size distribution of the sludge in the Prototype Nereda Utrecht.
:name: tab:granules
|sieve fraction      | MLSS                   | granule fraction    | 
| --- |--- |--- |
|&nbsp;&#181;m |  kg&nbsp;m<sup>-3</sup> | &hairsp;%     |  
|0 - 200             | 1.7                    | 16&hairsp;%   | 
|200 - 400           | 0.3                    | 3&hairsp;%    | 
|400 - 600           | 0.2                    | 2&hairsp;%    | 
|600 - 1000          | 0.4                    | 4&hairsp;%    | 
|1000 - 2000         | 3.2                    | 31&hairsp;%   | 
|>2000               | 4.6                    | 44&hairsp;%   |  
|Total                | 10.4                   | 100&hairsp;%  |  
```
### Microscopic analysis
A Leica Microsystems Ltd stereo zoom microscope (M205 FA) in combination with Leica Microsystems Qwin (V3.5.1) image analysis software was used to analyse the morphology of the sludge.

### Modelling of N<sub>2</sub> stripping
A mathematical model was developed to calculate the concentrations of dissolved nitrogen gas in the reactor. The solubility of nitrogen gas in water, $c_s$, is dependent on the partial pressure of nitrogen gas in the gas phase, $p$, and is calculated using Henry's law:

```{math}
:label: eq:henry
{c_s} = M \cdot {k_H} \cdot p
```

Here $k_H$ is the Henry's constant for the solubility of nitrogen gas in water and $M$ is the molar mass of nitrogen gas. The Henry's constant is a decreasing function of temperature, meaning that the solubility of nitrogen gas in water decreases with an increasing temperature. The partial pressure of nitrogen in the gas phase is both dependent on the gas fraction, $f$, and the pressure in the reactor, the latter being the sum of atmospheric pressure, $p_{atm}$ and hydrostatic pressure:

```{math}
:label: eq:pressure
	p=f \cdot \left( p_{atm} + x \cdot \rho \cdot g \right)
```

Here $x$ is the water depth, $\rho$ is the mixture density and $g$ is the gravitational acceleration.

The transfer of nitrogen gas between the air bubbles and the liquid is calculated by:

```{math}
:label: eq:gastransfer
	\frac{d c}{d t}=\alpha F \cdot {\left(k_L a\right)_N} \cdot \left( c_s - c \right)
```

Here $c$ is the nitrogen gas concentration in the water phase, $k_L$ is the mass transfer coefficient and $a$ is the interfacial area of the gas bubbles. The subscripts $O$ and $N$ indicate the values for oxygen gas and nitrogen gas. The mass transfer rate is corrected for effects of wastewater contaminants, $\alpha$, and fouling on the membrane aerators, $F$.
The value of the product of $k_L$ and  $a$ for oxygen transfer ${\left(k_L a\right)_O}$, is commonly measured during commissioning in full-scale wastewater treatment plants and depends on the temperature. For this study, a value of ${\left(k_L a\right)_O}$ including the effects of contaminants and fouling was used. For this, the values for $\alpha$ and $F$ were set to 1.

This empirical value of ${\left(k_L a\right)_O}$ can be used to derive a value for nitrogen gas by using Higbie's penetration theory {cite:p}`Higbie1935`. Based on this model the following relation between the $k_La$ for oxygen gas and nitrogen gas and the diffusion coefficient for oxygen gas ($D_O$) and nitrogen gas ($D_N$) for can be derived:

```{math}
:label: eq:convertkla
	\frac{\left( k_L a \right)_O}{\left(k_L a\right)_N} =\sqrt{\frac{D_O}{D_N} }
```

Both the diffusion coefficient and the Henry coefficient need to be corrected for temperature. For the diffusion coefficient this is based on the Stokes-Einstein equation {cite:p}`Einstein1905`. In this equation the diffusion coefficient $D$ is related to the temperature $T$ and the dynamic viscosity $\mu_T$:

```{math}
:label: eq:stokeseinstein
	D(T) = D_0 \frac{T}{T_0} \frac{\mu _{0}}{\mu _{T}}
```

The viscosity is also depending on temperature according to equation the Vogel-Fulcher-Tammann equation {cite:p}`Dagdug2000`, in which parameters A, B and C are empirical parameters:

```{math}
:label: eq:VogelFulcherTammann
	\mu(T) = \mathrm{e}^{A+\frac{B}{C+T}}
```

The Henry coefficient is corrected for temperature using the van 't Hoff equation {cite:p}`VantHoff1884`, in which $k_{H0}$ is the Henry coefficient at reference temperature, $T_0$ is the reference temperature and $H_c$ is the temperature correction factor:

```{math}
:label: eq:vanthoff
	k_H\left(T\right) = k_{H0} \mathrm{e}^{-k_{Hc} (\frac{1}{T} - \frac{1}{T_0}) }
```

The stripping of nitrogen gas is done by aeration of the reactor with fine bubble aeration. This leads to transport of dissolved nitrogen gas through the reactor. A simple axial dispersion model can be used to describe the liquid backmixing of dissolved nitrogen gas in the reactor {cite:p}`Degaleesan1998`, in which $x$ is the water depth.

```{math}
:label: eq:liquidbackmixing
	\frac{d c}{d t} = D_{ax,1} \frac{d^2 c}{d x^2}
```

The axial dispersion coefficient, $D_{ax,1}$, is a lumped coefficient, containing the effect of both turbulent dispersion and global convective recirculation in the reactor. Molecular diffusion in this case is neglected due to an expected limited impact. A tracer experiment with ammonium was used to determine the value of $D_{ax,1}$.

To describe the transfer of nitrogen gas between the air bubbles and the water phase, equation {eq}`eq:convertkla` is substituted in equation {eq}`eq:gastransfer`. If this equation is combined with the transport of nitrogen gas in the water phase according equation {eq}`eq:liquidbackmixing` a description for the stripping of nitrogen in a 1D bubble column is constructed:

```{math}
:label: eq:strippingofnitrogengas
	\frac{d c}{d t} = D_{ax,1} \frac{d^2 c}{d x^2} + \alpha F \cdot \left( k_L a \right)_O  \sqrt{\frac{D_N}{D_O} }  \cdot \left( c_s(x) - c \right)
```

The saturation concentration for nitrogen gas according to equation {eq}`eq:henry` can be combined with the actual concentration to calculate the nitrogen gas deficit in the bulk liquid, $c_{d}$.

```{math}
:label: eq:buffercapacity
	c_{d}= c_s-c
```

When over-saturation occurs during aeration (i.e. the actual concentration $c$ is higher than $c_s$ at ambient pressure and temperature), it is assumed that N<sub>2</sub> gas bubbles are formed immediately and efficiently stripped out of the bulk liquid. This is modelled by artificially increasing the local $k_La$ with an order of magnitude.

### Modelling of mixing during imperfect plug flow feeding
During feeding the bulk liquid in the reactor is pushed up towards the top of the reactor where the overflow weirs are situated.  To describe the transport of nitrogen gas during feeding, the same axial dispersion model of equation {eq}`eq:liquidbackmixing` is used with a different value for $D_{ax}$. Also an additional term is added to describe the transport of nitrogen gas through convection. Here, $v$ is the upflow velocity of the liquid in the reactor. The value of $D_{ax,2}$ was experimentally established by measuring a step response curve with ammonium as a tracer.

```{math}
:label: eq:plugflow
	\frac{d c}{d t} = D_{ax,2} \frac{d^2 c}{d x^2} + v \frac{d c} {d x}
```

The influent is fed from the bottom of the reactor. It is assumed that the influent concentration of dissolved nitrogen is equal to the equilibrium concentration of nitrogen gas at atmospheric pressure. During the feeding phase denitrification can take place. The denitrification rate depends on many parameters, but in this case a lumped specific denitrification rate, $q$, is used. The specific denitrification rate was measured in the reactor in the days before the experiment, by measuring the decrease of the nitrate concentration during an anoxic phase in the cycle. This rate is multiplied by the biomass concentration, $c_X$, which is a function of the reactor depth.  The sludge bed is assumed to be in steady state and thus invariable in time. In the simulations it was assumed that the sludge bed occupies the lower 4 meters of the reactor and that the sludge is evenly distributed. We can then write equation {eq}`eq:plugflow` as follows:

```{math}
:label: eq:plugflowreaction
	\frac{d c}{d t} = D_{ax,2} \frac{d^2 c}{d x^2} + v \frac{d c} {d x} + q c_X(x)
```

In this model the water in the reactor can get over-saturated with nitrogen gas. This means that the local concentration of nitrogen gas, $c$, becomes larger than the local saturation concentration according to equation {eq}`eq:henry`. It is assumed that nitrogen gas bubbles are formed immediately after over-saturation.  Most likely supersaturation of nitrogen gas can occur, but the effect is assumed to be limited {cite:p}`Henze1993`.

All model parameters are given in {numref}`tab:modelParametersCh2`.

```{table} Model parameters.
:name: tab:modelParametersCh2
| Parameter                                                | Symbol                    | Value          | Unit                                     |  
| --- |--- |--- |--- |
| Henry's constant for N<sub>2</sub> (25&nbsp;&#176;C)   | $k_h$                     | 6.4&hairsp;x&hairsp;10<sup>-6</sup>  | mole m<sup>-3</sup> Pa <sup>-1</sup>  | 
| Temperature coefficient N<sub>2</sub>                          | $k_{hc}$                  | 1300           | K                                | 
| Molar mass N<sub>2</sub>                                       | $M$                       | 28             | g mole<sup>-1</sup>                   | 
| Gas fraction of N<sub>2</sub> in air                           | $f$                       | 0.78           | -                                        | 
| Atmospheric pressure                                     | $p_{atm}$                 | 101,325        | Pa                                       | 
| Density of water                                         | $\rho$                    | 1000           | kg m<sup>-3</sup>                   | 
| Gravity acceleration                                     | $g$                       | 9.81           |      m s<sup>-2</sup>    | 
| Alpha factor                                             | $\alpha$                  | 1              | -                                        | 
| Fouling factor                                           | $F$                       | 1              | -                                        | 
| Gas transfer rate for oxygen                             | ${\left(k_L a\right)_O}$  | 5.5            | h<sup>-1</sup>                         | 
| Diffusion coefficient \ch{O2} (25&nbsp;&#176;C)  | $D_O$                     | 2.10&hairsp;x&hairsp;10<sup>-9</sup>  | m<sup>2</sup> s<sup>-1</sup>             | 
| Diffusion coefficient N<sub>2</sub> (25&nbsp;&#176;C)  | $D_N$                     | 1.88&hairsp;x&hairsp;10<sup>-9</sup>   | m<sup>2</sup> s<sup>-1</sup>             | 
| Empirical coefficient A                                  | $A$                       | -10.6265       | -                                        | 
| Empirical coefficient B                                  | $B$                       | 578.919        | -                                        | 
| Empirical coefficient C                                  | $C$                       | -137.546       | -                                        | 
| Axial dispersion during aeration                         | $D_{ax,1}$                | 1.0&hairsp;x&hairsp;10<sup>-2</sup>    | m<sup>2</sup> s<sup>-1</sup>             | 
| Axial dispersion during feeding                          | $D_{ax,2}$                | 1.0&hairsp;x&hairsp;10<sup>-4</sup>    | m<sup>2</sup> s<sup>-1</sup>             | 
```

## Results

### Reactor operation
The data were collected between June 2015 and May 2016. In this period the reactor was running stable and without interruption with average effluent values of COD of 41&nbsp;mg&nbsp;L<sup>-1</sup>, N<sub>kj</sub>-N of 4.05&nbsp;mg&nbsp;L<sup>-1</sup>, NH<sub>4</sub><sup>+</sup>-N of 1.29&nbsp;mg&nbsp;L<sup>-1</sup>, NO<sub>3</sub><sup>-</sup>-N of 3.72&nbsp;mg&nbsp;L<sup>-1</sup>, P<sub>tot</sub>-P of 0.51&nbsp;mg&nbsp;L<sup>-1</sup> and PO<sub>4</sub><sup>3-</sup>-P of 0.26&nbsp;mg&nbsp;L<sup>-1</sup>, showing a highly efficient N and P removal of respectively 94&hairsp;% and 91&hairsp;%. The average granule size distribution is reported in {numref}`tab:granules`.  The sludge in the reactor mainly consisted of smooth granules larger than 1&nbsp;mm, which is also shown by the microscopic image of the sludge in {numref}`fig:sludge in reactor`A. The water temperature was in the range of 9&hairsp;-&hairsp;23&nbsp;&deg;C.

```{figure} figures/chapter-2/picture_sludge.png
---
name: fig:sludge in reactor
---
Biomass in the Prototype Nereda<sup>&#174;</sup> Utrecht: (A) granules in the reactor, (B) light microscopic picture of effluent suspended solids, (C) scum on top of the reactor after installation of the baffles, (D) biomass from the top of the reactor.
```

### Degasification of nitrogen gas
Due to denitrification and upward transport of liquid (decreasing local pressure) over-saturation of the water phase with nitrogen gas can occur, leading to gas bubble formation in the feeding/decanting period. To confirm that over-saturation of nitrogen gas is present during parts of the cycle an experiment was performed. Two comparable batches were fed to the reactor. The batch sizes are given as {term}`VER<VER>`, which is the ratio between the batch size (f.e. 400&nbsp;m<sup>3</sup>) and the volume of the reactor (1000&nbsp;m<sup>3</sup>). Before the first batch (batch 1) the reactor was intensely aerated before feeding the reactor, while in the second batch (batch 2) this stripping phase was omitted. The gas stripping period was 30 minutes long, with an air flow of 800&nbsp;m<sup>3</sup>&nbsp;h<sup>-1</sup>. This high value was chosen to strip a maximum amount of nitrogen gas. The process conditions in the two batches were comparable (batch 1: volumetric exchange ratio 40&hairsp;%, nitrogen removed in previous batch 13.8&nbsp;mg&nbsp;L<sup>-1</sup>, average temperature 13.6&nbsp;&#176;C; batch 2: volumetric exchange ratio 40&hairsp;%, nitrogen removed in previous batch 13.9&nbsp;mg&nbsp;L<sup>-1</sup>, average temperature 13.5&nbsp;&#176;C).  The effect of a stripping phase is clearly illustrated in figure {numref}`fig:EffectStripping`, showing the effluent turbidity for both batches. Batch 1 showed an overall lower level effluent turbidity with a turbidity slightly decreasing over the batch, with an average value of 4.9 FNU. The turbidity in batch 2 was overall higher than in batch 1, with an average value of 21.0 FNU. At a volumetric exchange ratio of 30&hairsp;% the effluent turbidity started to increase up to a value of 48.5 FNU at the end of batch 2. In {numref}`fig:degassificationscum` photographs recorded by a security camera are showing the gradual formation of a scum layer due to degasification during batch 2.

```{figure} figures/chapter-2/figure_rising_sludge_event.svg
---
name: fig:EffectStripping
---
Turbidity of the effluent in a batch with gas stripping (batch 1) and without gas stripping (batch 2).
```

```{figure} figures/chapter-2/picture_degassification_event.png
---
name: fig:degassificationscum
---
Degasification and the resulting floatation of biomass during feeding in a batch without stripping: (A) VER = 0&hairsp;% (B) VER = 20&hairsp;% (C) VER = 40&hairsp;%.
```

### Stripping of nitrogen gas
Dissolved nitrogen gas can be stripped out by aerating right before the feeding phase to prevent rising of biomass as is shown above.
Equation {eq}`eq:strippingofnitrogengas`, together with equation {eq}`eq:henry` and {eq}`eq:pressure` for pressure correction, equation {eq}`eq:stokeseinstein`, equation {eq}`eq:VogelFulcherTammann` and equation {eq}`eq:vanthoff` for temperature correction and equation {eq}`eq:convertkla` for the conversion of the k<sub>L</sub>a can be used to evaluate the effect of the stripping period on the dissolved N<sub>2</sub> concentration in the reactor.

In {numref}`fig:modelstripping` the effect of stripping of an initially fully N<sub>2</sub> saturated situation in the reactor is shown at a temperature of 20&nbsp;&#176;C. The dissolved nitrogen gas concentration in the reactor (top at 0&nbsp;m, bottom at 7&nbsp;m) is shown. The figure shows three coloured zones: the blue zone marks the area where the nitrogen gas concentration is lower than the equilibrium concentration for air (i.e. no degasification expected). The grey zone marks the area where the nitrogen gas concentration is higher than the equilibrium concentration for pure nitrogen gas (i.e. degasification expected). The white zone marks the area where only a partial nitrogen gas deficit exists. The boundary between the blue area and the white area is calculated according to equation {eq}`eq:henry` and equation {eq}`eq:pressure` with a gas fraction of nitrogen gas in air at ambient water pressure and temperature (f=78&hairsp;%). The boundary between the white and the grey area is calculated in a similar manner, but with pure nitrogen gas bubbles (f=100&hairsp;%).

The mixing of the reactor has a large impact on the effect of the stripping phase. Dissolved nitrogen gas is convectively transported through the reactor, leading to an over-saturated situation near the top of the reactor and an undersaturated situation near the bottom of the reactor. When the aeration continues, the nitrogen gas is slowly stripped out of the reactor and a N<sub>2</sub> deficit is created at the bottom of the tank. After 15 minutes, due to the mixing, the N<sub>2</sub> concentration near the bottom of the reactor is lower than the air equilibrium concentration at 7 meters water depth. However, near the top of the reactor the N<sub>2</sub> concentration is still over-saturated. Even after 60 minutes of aeration the nitrogen concentration is still at saturation concentration near the top of the reactor due to upmixing of dissolved N<sub>2</sub> gas. Note that for operational conditions over-saturation at the top of the reactor is not important since there is no sludge bed/blanket near the top of the reactor during effluent withdrawal.

```{figure} figures/chapter-2/figure_model_stripping.svg
---
name: fig:modelstripping
---
Stripping of N<sub>2</sub> gas from fully saturated situation (A) and after 5 minutes (B), 15 minutes (C) and 60 minutes of stripping (D) at 13.5&nbsp;&#176;C. Black solid line: the actual N<sub>2</sub> concentration, grey area: N<sub>2</sub> concentration above saturation, blue area: N<sub>2</sub> concentration below equilibrium with air, boundary between grey area and white area: N<sub>2</sub> concentration at equilibrium with pure nitrogen gas at ambient water pressure, boundary between blue area and white area: N<sub>2</sub> concentration at equilibrium with air at ambient water pressure.
```

```{figure} figures/chapter-2/figure_model_longstrip_feeding.svg
---
name: fig:modelfeedingwithstripping
---
Effect of feeding after a stripping phase on the dissolved nitrogen gas concentration from the start (A), after 15 minutes (B), after 30 minutes (C) and after 50 minutes (D). T = 13.5&nbsp;&#176;C, r = 0.25&nbsp;mg&hairsp;g<sup>-1</sup>&hairsp;h<sup>-1</sup>.
		Black solid line: the actual N<sub>2</sub> concentration, black dashed line: biomass concentration, grey area: N<sub>2</sub> concentration above saturation, blue area: N<sub>2</sub> concentration below equilibrium with air, boundary between grey area and white area: N<sub>2</sub> concentration at equilibrium with pure nitrogen gas at ambient water pressure, boundary between blue area and white area: N<sub>2</sub> concentration at equilibrium with air at ambient water pressure.
```		

```{figure} figures/chapter-2/figure_model_nostrip_feeding.svg
---
name: fig:modelfeedingnostripping
---
Effect of feeding without a prior stripping phase on the dissolved nitrogen gas concentration from the start (A), after 15 minutes (B), after 30 minutes (C) and after 50 minutes (D). T = 13.5&nbsp;&#176;C, r = 0.25&nbsp;mg&hairsp;g<sup>-1</sup>&hairsp;h<sup>-1</sup>.
		Black solid line: the actual N<sub>2</sub> concentration, black dashed line: biomass concentration, grey area: N<sub>2</sub> concentration above saturation, blue area: N<sub>2</sub> concentration below equilibrium with air, boundary between grey area and white area: N<sub>2</sub> concentration at equilibrium with pure nitrogen gas at ambient water pressure, boundary between blue area and white area: N<sub>2</sub> concentration at equilibrium with air at ambient water pressure.
```

### Degasification during feeding
The effect of denitrification during feeding on degasification of nitrogen gas was also evaluated by extending the model according to equation {eq}`eq:plugflowreaction`. In {numref}`fig:modelfeedingwithstripping` an example is shown for a batch comparable with the previously described batch 1 in which a stripping phase of 30 minutes is applied, with T = 13.5&nbsp;&#176;C, r = 0.25&nbsp;mg&hairsp;g<sup>-1</sup>&hairsp;h<sup>-1</sup>.

The model shows limited over-saturation during the feeding period of 1 hour, but the over-saturation only occurs above the sludge blanket so rising of sludge due to bubble formation is not likely to happen.

If the stripping phase is reduced to 5 minutes, again with T = 13.5&nbsp;&#176;C, r = 0.25&nbsp;mg&hairsp;g<sup>-1</sup>&hairsp;h<sup>-1</sup>, a situation comparable with the above described batch 2 experiment can be modelled.  The results are shown in {numref}`fig:modelfeedingnostripping`. The water in the vicinity of the sludge blanket is almost immediately slightly over-saturated with nitrogen gas. After 30 minutes the top of the sludge blanket is fully over-saturated with nitrogen gas, which most likely will lead to rising sludge as the escaping nitrogen bubbles get caught by small flocs near the supernatant - sludge interface.


### Identification of suspended solids in the effluent
The suspended solids present in the effluent were examined under a stereo-zoom microscope to determine the characteristics and possible origin. {numref}`fig:sludge in reactor`b and {numref}`fig:sludge in reactor`d show that the suspended solids in the effluent are small dense light brown flocs. No filamentous organisms like _Thiothrix_ spp. or _Microthrix_ spp. were observed that would normally be associated with bad settling sludge ({numref}`fig:sludge in reactor`d). It was also observed that after light shaking of the sample flask the suspended solids quickly settled to the bottom indicating that the suspended solids were able to settle well.

### Effect of the vertical baffle
During the first experimental period (between April 2013 and May 2015)  the average suspended solids effluent concentration was 30&nbsp;mg&nbsp;L<sup>-1</sup> with a 50-percentile value of 19.8&nbsp;mg&nbsp;L<sup>-1</sup>. In the same period, many values below 10&nbsp;mg&nbsp;L<sup>-1</sup> were also recorded with a 25-percentile value of 9.3&nbsp;mg&nbsp;L<sup>-1</sup>.
On the 3rd of June 2015 vertical baffles were installed in front of the overflow weirs. Composite samples of the effluent of the reactor were taken in the period immediately before and after the baffles were installed; i.e. under similar operational and sludge characteristics. {numref}`fig:EffectBaffle` shows the effluent suspended solids in this period. In the period immediately before installation of the baffles the average effluent suspended solids concentration was 23&nbsp;mg&nbsp;L<sup>-1</sup>, which is 10&hairsp;% of the influent suspended solids concentration. In the period directly after installation of the baffles only 1 sample was above 10&nbsp;mg&nbsp;L<sup>-1</sup> with a total average of 7.2&nbsp;mg&nbsp;L<sup>-1</sup>. In the period June 2015 to May 2016, 175 composite influent and effluent samples were taken by the local water authority. The suspended solids concentration in the influent was 230&hairsp;&plusmn;&hairsp;180 mg&nbsp;L<sup>-1</sup> and the concentration of effluent suspended solids was 
7.8&hairsp;&plusmn;&hairsp;3.8 mg&nbsp;L<sup>-1</sup> with a 95-percentile value of 13.6&nbsp;mg&nbsp;L<sup>-1</sup>.
The average removal efficiency of suspended solids was 97&hairsp;%. After installation of the baffles a thin layer of scum was present in most batches during feeding ({numref}`fig:sludge in reactor`c), but in this period no built up of scum was observed. The thin layer of scum always disappeared in the first few minutes of the reaction phase of the cycle.

```{figure} figures/chapter-2/figure_effect_baffle.svg
---
name: fig:EffectBaffle
---
Suspended solids concentration in the effluent before and after installation of vertical baffle in front of the overflow weirs.
```

## Discussion
### Comparison with floc systems
In this study we examined the main processes for production of effluent suspended solids in full-scale aerobic granular sludge reactors. The problem of rising sludge is known from both continuously fed activated sludge systems {cite:p}`Henze1993` as from sequencing batch reactors {cite:p}`Tora2011`. Comparison of the flow patterns in a secondary clarifier and the AGS reactor reveals some important differences ({numref}`fig:comparison_clarifier_ags`). The outflow from an aeration tank towards a secondary clarifier generally flows over a weir making the water pressure almost atmospheric and generating a lot of turbulence. This is an effective way to remove at least part of the dissolved nitrogen gas. Subsequently, the water from the aeration tank flows into the secondary clarifier through the centre well where the water pressure is close to atmospheric pressure again. In the clarifier the flow splits into effluent and return sludge. The return sludge is removed from the bottom of the clarifier. During dry weather conditions a limited amount of sludge is present in the clarifier and this sludge will be near the bottom of the clarifier at a water pressure well above atmospheric pressure. If the water pressure increases at higher water depth, automatically the nitrogen gas deficit increases. Thus, if nitrogen gas is formed in a clarifier due to denitrification this will mainly take place at the bottom of the clarifier, where a relatively high nitrogen gas deficit is present. This is probably why degasification in a clarifier is not a very common problem and is only known from high loaded systems at high temperatures with high denitrification rates {cite:p}`Sarioglu1996` or when the inflow to the clarifier is not degassed at an overflow weir. In the AGS reactor the influent is fed from the bottom of the reactor, pushing the with nitrogen gas saturated water in the reactor upwards to lower water pressure. This process is comparable with the process occurring in a sequencing batch reactor, where degasification can occur while decanting the effluent and thereby decreasing the water pressure. Thus, while feeding the reactor, the upwards moving liquid gets a lower saturation concentration for nitrogen gas, while in a clarifier it gets increased.
In the AGS reactor during feeding, denitrification of remaining nitrate on storage polymers by GAO and PAO like organisms, built up in previous cycles, can occur {cite:p}`Kuba1996`. The combination of a lower nitrogen gas deficit due to pressure decrease and a higher denitrification potential make the AGS reactor more susceptible for degasification of nitrogen gas in comparison to a clarifier. Therefore, washout of suspended solids due to degasification of nitrogen gas is less common in clarifiers than in AGS reactors.

```{figure} figures/chapter-2/degasification_clarifier.svg
---
name: fig:comparison_clarifier_ags
---
Comparison of flow in an AGS reactor (left) and flow in a conventional aeration tank and clarifier (right).
```

### Effect of N<sub>2</sub> stripping
Rising of sludge due to degasification of dissolved N<sub>2</sub> gas can cause elevated levels of suspended solids in the effluent of activated sludge and AGS plants. Experimentally it was shown that a nitrogen gas stripping phase just before the influent feeding phase was effective to prevent rising of sludge in the AGS process. The developed mathematical model shows that a limited amount of N<sub>2</sub> gas deficit can be reached by applying a stripping phase. When the water is pushed up during the feeding phase almost immediate over-saturation occurs when no stripping phase is applied.

The model presented by Henze et al. {cite:p}`Henze1993` only showed a steady state N<sub>2</sub> gas deficit in an unmixed situation. This model was extended to show the effect of non-steady state aeration and feeding. A convection/dispersion term was added to the model to describe both mixing due to aeration of the reactor and the plug flow behaviour of the AGS reactor during feeding. The model shows that the local dissolved N<sub>2</sub> gas concentration changes over time and depth of the reactor. The maximum deficit for N<sub>2</sub> gas depends highly on the temperature, as do the denitrification rates. The model can easily be extended to calculate the risk of rising sludge based on temperature, batch size and aeration history of the reactor. Denitrification rates increase with temperature and the N<sub>2</sub> gas deficit will decrease with temperature. At temperatures above 20&nbsp;&#176;C the need for a stripping phase increases. It should be realized that for the denitrification during the settling/feeding phase mainly residual COD from the previous cycles is used. The COD containing influent is replacing the nitrate containing liquid in the reactor. Therefore, influent COD and nitrate will only mix after the feeding phase when the aeration is switched on.

### Effect of the scum baffle
Introduction of the vertical scum baffles in front of the effluent weir lowered the effluent suspended solids concentration from 23&nbsp;mg&nbsp;L<sup>-1</sup> to 7&nbsp;mg&nbsp;L<sup>-1</sup>. Analyses of the suspended solids in the effluent before installation of the baffles did not show any significant presence of granules or filamentous bacteria.  Microscopic analyses only revealed the presence of small sludge flocs. The thin layer of sludge present on the surface of the reactor during feeding, observed after installation of the baffles apparently was the result of the blocking of wash-out of floating sludge by the baffles. The same effect is known from clarifiers in activated sludge systems {cite:p}`Eddy2014`.

It was shown that at a MLSS concentration of 10.1&nbsp;g&nbsp;L<sup>-1</sup> and an influent suspended solids of 230&nbsp;mg&nbsp;L<sup>-1</sup> an effluent suspended solids concentration below 10&nbsp;mg&nbsp;L<sup>-1</sup> was obtained over long-term operation. The flocs present in the layer on top of the reactor are assumed to be grown in the reactor. Apparently, not all biomass grown in the reactor is granular. The flocculent mass likely consists of non-biodegradable inert COD from the influent and detached biomass from the granules. This is also shown by the fractionation of the sludge showing an average 16&hairsp;% of mass smaller than 200&nbsp;&#181;m.

The influent of the reactor contained an average of 230&nbsp;mg&nbsp;L<sup>-1</sup> of TSS after screening. Since the only pre-treatment of the reactor was a 6&nbsp;mm perforated plate screen, some floating material from the sewerage will end up in the reactor. Although the influent consists merely of domestic wastewater, the sewage of the Overvecht district is known to contain relatively large fraction of fat. Some fatlike particles were observed in the reactor, but in the period of 10 months in which the experiment was run, no build-up of scum  or fat on the reactor was observed. Apparently, the fat particles were converted or removed with the excess sludge.

The reported values of effluent suspended solids of 20&nbsp;mg&nbsp;L<sup>-1</sup> for the Garmerwolde plant {cite:p}`Pronk2015` are comparable with the levels measured in this study before installation of the vertical baffles in front of the effluent weirs. Since the Garmerwolde plant mainly treats domestic sewage and also the pre-treatment of the wastewater is comparable, these levels of effluent suspended solids are to be expected. Also reported values for other plants ({numref}`tab:reportedsuspendedsolids`) were in the range of
10&hairsp;-&hairsp;20 mg&hairsp;L<sup>-1</sup> and thus comparable with the values measured in this study before installation of the vertical baffle. This value is to be expected from a full-scale aerobic granular sludge reactor on domestic wastewater if no baffle is present. The Gansbaai plant is the exception, with a value of 5&nbsp;mg&nbsp;L<sup>-1</sup>, but detailed information is not available. Baffles have proven to be an effective and economic way to keep effluent suspended solids below 10&nbsp;mg&nbsp;L<sup>-1</sup>, similar to well operated secondary clarifier effluents.

## Conclusions

In this study, two main processes have been identified that can contribute to elevated suspended solids concentration in the effluent of the aerobic granular sludge process in practice. These processes also play an important role in suspended solids control in secondary clarifiers of activated sludge plants. Two solutions known from operation of secondary clarifiers could successfully be incorporated into the AGS process leading to low concentration of suspended solids in the effluent. The implementation of nitrogen stripping, before the settling period, avoids gas bubble formation during feeding and thus the floatation of lighter biomass. A mathematical model describing degasification was developed that explains the observations of higher suspended solids concentrations in the effluent when treating sewage. Introduction of a vertical baffle in front of the effluent weir showed to be an effective measure to keep floating sludge and fat-like particle in the reactor, resulting in an effluent suspended solids concentration lower than 10&nbsp;mg&nbsp;L<sup>-1</sup> with an average influent suspended solids concentration of 230&nbsp;mg&nbsp;L<sup>-1</sup>. This was achieved with high biomass concentrations (10&nbsp;g&nbsp;L<sup>-1</sup>) and a high granulation grade (84&hairsp;%).

<!-- ## References
```{bibliography}
:filter: docname in docnames
``` -->