# A carrying capacity and efficiency optimization model for freight cargo trains

This project presents a tool for Freight Trains Capacity optimization, presented as a tool to generate a container loading plan.

## Trains, wagons and containers

In today’s era of mega vessels in ocean container shipping, when thousands of containers can be discharged from a single vessel call, one of the key challenges at marine terminals is minimizing container dwell times, i.e. the times containers spend in a terminal’s yard, so that terminals can opérate within their optimum capacity. In other words, containers should ideally leave the terminal as quickly as possible once offloaded from vessels ([Talley and Ng, 2016](https://www.sciencedirect.com/science/article/abs/pii/S1366554515002276)).

<p align="center">
  <img width="700" src="https://github.com/marceloigallegos/Opt_CapacityFreightTrains/blob/main/mdImages/Figura1.png">
</p>

Containers leave marine terminals most commonly over the road. However, due to the increasing number of containers discharged per vessel call, the limited gate hours, growing road congestion and assciated health and environmental concers, port authorities and terminal operators increasingly recognize the need to move containers by (on-dock) rail. For example, the Port of New York-New Jersey hopes to increase its rail transport share to 20% by 2020, and the Port of Virginia sets its target at more than 40% ([Hutchins, 2017](https://www.joc.com/rail-intermodal/intermodal-shipping/charleston-virginia-ports-deepen-intermodal-rail-reach_20170710.html)).

In the United States, containers are commonly transported on double stack trains, where containers can be stacked two high on rail cars. Due to the higher stacking ability, double stack rail service is more cost efficient than conventional single stack, container on flat car trains ([Talley, 2009](https://www.routledge.com/Port-Economics/Talley/p/book/9781138952195)). Double stack rail service is also available in other selected countries such as Australia, Canada, China, India and Panama, but typically at a smaller scale. Unfortunately, it is not uncommon to see double stack trains whose space have not been completely utilized. Not only does this negatively impact the environmental footprint of rail transportation, will also lead to longer container dwell times at marine terminals ([Ng and Talley, 2020](https://www.sciencedirect.com/science/article/abs/pii/S0968090X20301479)).

## Model

### Dependencies
- Matplotlib
- Ortools (linear solver)
- Pillow (PIL, for the use of images).

X

<p align="center">
  <img width="700" src="https://github.com/marceloigallegos/Opt_CapacityFreightTrains/blob/main/mdImages/Figura2.png" alt="Texto 2">
  <br>**Representación gráfica de las posibles configuraciones resultantes**<br>
</p>
