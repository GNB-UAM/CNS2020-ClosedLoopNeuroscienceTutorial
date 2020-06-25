# Tools and techniques to bridge the gap between models and closed-loop neuroscience experiments

CNS 2020 half-day tutorial - July 18th

16:00 - 19:00 Berlin Time

10:00am - 1:00pm New York time

## Organizers

Pablo Varona (pablo.varona@uam.es)

Manuel Reyes Sanchez (manuel.reyes@uam.es)

Rodrigo Amaducci (rodrigo.amaducci@uam.es)

*Grupo de Neurocomputación Biológica. Escuela Politécnica Superior. Universidad Autónoma de Madrid*

http://www.ii.uam.es/~gnb

## Tutorial Description

Models in computational neuroscience are typically used to reproduce and explain
experimental findings, to draw new hypotheses from their predictive power, to undertake the
low observability of the brain, etc. However, computational models can also be employed to
interact directly with living nervous systems, which is a powerful way of unveiling key neural
dynamics by combining experimental and theoretical efforts. However, protocols that
simultaneously combine recordings from living neurons and input/outputs from computational
models are not easy to design or implement. In this tutorial, we will describe several tools and
techniques to build such kind of open and closed-loop interactions: from basic dynamic-clamp
approaches to build hybrid circuits to more complex configurations that can include several
interacting living and artificial elements. We will emphasize the need of open-source real-time
software technology for some of these interactions.

In particular, we will focus on two software packages that can implement closed-loop
interactions between living neurons and computational neuroscience models. The first one,
RTHybrid, is a solution to build hybrid circuits between living neurons and models. This
program, developed by the organizers, includes a library of neuron and synapse models and
different algorithms for the automatic calibration and adaptation of hybrid configurations. The
second software tool, RTXI, allows to program specific modules to implement a wide variety of
closed-loop configurations and includes many handy modularization and visualization tools.
Both programs can be used in very wide contexts of hybrid experimental design and deal with
real-time constraints. During the tutorial, we will show how to install and use these programs
in standard computer platforms, and we will provide attendees the possibility of building and
testing their first designs.

## Software tools

RTHybrid: https://github.com/GNB-UAM/RTHybrid

RTXI: http://rtxi.org/

## Tutorial content and schedule

| Time                                                     | Title                                    | Speaker      |
|----------------------------------------------------------|------------------------------------------|--------------|
| 16:00-16:30h Berlin Time <br> 10:00am-10:30am New York Time | Introduction to Closed-loop Neuroscience | Pablo Varona |
| 16:30-17:00h Berlin Time <br> 10:30am-11:00am New York Time | Hybrid Circuits: interacting living neurons, model neurons and robots | Rodrigo Amaducci |
| 17:00-17:30h Berlin Time <br> 11:00am-11:30am New York Time | Automatic adaptation and mappings of hybrid circuits | Manuel Reyes-Sánchez |
| 17:00-17:30h Berlin Time <br> 11:00am-11:30am New York Time | Automatic adaptation and mappings of hybrid circuits | Manuel Reyes-Sánchez |
| 17:30-17:45h Berlin Time <br> 11:30am-11:45am New York Time | Break |
| 17:45-19:00h Berlin Time <br> 11:45am-13:00pm New York Time | Software installation, software demos, interactive discussion | Rodrigo Amaducci <br> Manuel Reyes-Sánchez |

## References and background reading

M. Reyes-Sanchez, R. Amaducci, I. Elices, F.B. Rodriguez, P. Varona. 2020. Automatic
adaptation of model neurons and connections to build hybrid circuits with living networks.
Neuroinformatics.

R. Amaducci, M. Reyes-Sanchez, I. Elices, F.B. Rodriguez, P. Varona. 2019. RTHybrid: A
Standardized and Open-Source Real-Time Software Model Library for Experimental
Neuroscience. Frontiers in Neuroinformatics 13:11.

Patel, Y. A., George, A., Dorval, A. D., White, J. A., Christini, D. J., &amp; Butera, R. J. 2017. Hard real-
time closed-loop electrophysiology with the Real-Time eXperiment Interface (RTXI). PLoS
Computational Biology, 13(5), e1005430.

P. Varona, D. Arroyo, F.B. Rodriguez, T. Nowotny. Online event detection requirements in
closed-loop neuroscience. In Closed-Loop Neuroscience. El Hady A. (Ed), Academic Press. 2016.
ISBN 9780128024522.

P. Chamorro, C. Muñiz, R. Levi, D. Arroyo. F.B. Rodriguez, P. Varona. 2012. Generalization of
the dynamic clamp concept in neurophysiology and behavior. PLoS ONE 7(7): e40887.

---

<a target="_blank" rel="noopener noreferrer" href="https://github.com/GNB-UAM/RTHybrid"> <img src="https://github.com/GNB-UAM/RTHy_plot_tool/raw/master/assets/logo_rthy.png" width="100" height="100"> </a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	
<a target="_blank" rel="noopener noreferrer" href="https://github.com/GNB-UAM"> <img src="https://github.com/GNB-UAM/RTHy_plot_tool/raw/master/assets/logo_gnb.png" width="100" height="100"> </a>