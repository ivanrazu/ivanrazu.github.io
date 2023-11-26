---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /research
---

I am an applied mathematician specializing in the use of mathematical tools to investigate biological
problems. My primary line of research focuses in understanding the intricate relationship
between immunometabolism and its implications in infectious diseases and inflammation using
applied analysis and dynamical systems. More generally, I am interested in developing data-driven
mechanistic models for understanding the underlying biology of specific biological processes including
the dynamics of infectious diseases in populations and in hosts. When the complexity of
the model allows it, I use dynamical systems theory and applied analysis techniques including parameter
bifurcation to extract important information about the problem. In most cases however,
these models cannot be solved analytically and it is necessary the use of existent or own written
numerical packages. Analytic or numerical analysis of the model can reveal rich insights about
the biology of the problem that would allow us to address relevant biological questions as well as
generate and test new hypothesis. I am also interested in using statistical methods and machine
learning algorithms to understand data patterns in clinical or experimental data, which can later
inform the development of mathematical models to comprehend underlying biological mechanisms
and generate/test hypotheses to be validated through further experiments. 

## Projects

### Mathematical Modeling of Energy Consumption in the Acute Inflammatory Response.

* Several studies have found a relation between sepsis and low levels of adenosine triphosphate (ATP) combined with overproduction of lactate and nitric oxide (NO). In this project we developed a system of ordinary differential equations to study the dynamics of the acute inflammatory response and its interactions with the production and demand of ATP. 
We also explored some altered metabolic states such as hypoglycemia, hyperglycemia, and hypoxia in the presence of sepsis obtaining consistent resuts with the literture.

                                                                          
<img src="/images/wiring_diagram_2.png" alt="drawing" width="400"/>    <img src="/images/bif_diagram (1).png" alt="drawing" width="400"/>

(Left) Interactions between the eight variables of the system of equations in the model. P corresponds
to pathogens, D tissue damage, N phagocytes, CA anti-inflammatory mediators, X nitric oxide, L lactate, and ATP
adenosine triphosphate. (Right) Bifurcation diagram for model equations on. Equilibrium states are illustrated with
red solid curves (stable), shown with dashed curves (unstable), or not shown at all if non-physiological. The three
stable equilibrium states correspond to healthy, aseptic (infection is resolved but inflammation persists), and septic
(infection and inflammation persist) states.

### A Data-driven Mathematical Study of the Role of Energy in Sepsis.

* In a subsequent publication we further extended our model to include quantities that were measured from the blood of experimental
subjects exposed to bacteria. By fitting model dynamics to experimental data, we derived
parameter distributions corresponding to individual subjects’ responses as well as a parameter
ensemble representing the full cohort of experimental subjects. We found important
differences across survivors and non-survivors and identified the role of energetics in each of
the groups and determined the possible causes of death of the non-survivor cohort.

<img src="/images/Wiring_diagram_extended.png" alt="drawing" width="700"/>

Interactions between the 12 variables of the system of equations in the model. P corresponds
to pathogens, D tissue damage, N phagocytes, CA anti-inflammatory mediators, X nitric oxide, L lactate, ATP
adenosine triphosphate, LPS lipopolysachiride, Nit nitrate, G glucose, Y pyruvate, and Gly glycogen.

 <img src="/images/Ab (1).jpg" alt="drawing" width="400"/>     <img src="/images/N (1).jpg" alt="drawing" width="400"/>     

Predicted intervals of the ATP and phagocytes model trajectories obtained with parameters
from survivor (blue) and non-survivor (red) distributions. The model suggested survivor individuals were able to
recover their ATP loss during the infection, whereas in non-survivors energy depletion was a potential reason for
death. Similarly, phagocyte activity remained elevated in non-survivors while baseline levels were attained in the
survivor cohort


