# NASSCOM-VLSI-DESIGN-AND-PLANNING

## Day - 1

L1 - Introduction to QFN-48 Package, chip, pads, core, die and IPs <br>
L2 - Introduction to RISC-V <br>
L3 - From Software Applications to Hardware 

L1 - Introduction to all components of open-source digital asic design <br>
L2 - Simplified RTL2GDS flow <br>
L3 - Introduction to OpenLANE and Strive chipsets <br>
L4 - Introduction to OpenLANE detailed ASIC design flow

L1 - OpenLANE Directory structure in detail <br>
L2 - Design Preparation Step <br>

![prep](https://github.com/user-attachments/assets/5e4eb3e2-81cf-4d77-a60d-4e1a3103c7bc) <br>

L3 - Review files after design prep and run synthesis <br>

![synthesis](https://github.com/user-attachments/assets/d6fb495e-e7bc-4808-ac1e-d42fe75aab14) <br>

L4 - OpenLANE Project Git Link Description <br>
L5 - Steps to characterize synthesis results <br>

![stats](https://github.com/user-attachments/assets/64671537-dd5a-4e3d-a475-3424f3956048) <br>
```
Number of D Flipflops : 1613
Total number of Cells : 14876
FF Ratio : 0.1084
FF Percentage : 10.84 %
```

## Day - 2 
L1 - Steps to run floorplan using OpenLane

![floorplan_def](https://github.com/user-attachments/assets/554c37a9-1cd9-4534-b63e-a366890d3cb5)
```
Die Area = 660.685 um * 671.405 um
```
![magic](https://github.com/user-attachments/assets/ff53e80d-2ebe-46f0-9aa6-fa724d144932)

![magic_layer](https://github.com/user-attachments/assets/b930442f-2562-4ad4-bd95-e1eb9dac1e36) 

L2 - Steps to perform placement in OpenLane

![placement_magic](https://github.com/user-attachments/assets/cfd31da8-9336-4cdf-befc-2cf31b2e7a7e)

## Day - 3

Exploring SKY130's basic layers

![magic_inverter](https://github.com/user-attachments/assets/dfdaba4b-ca50-4754-bff6-bbbfb79965e7)

```
Extracting to spice
```
![spice_extract](https://github.com/user-attachments/assets/3205086f-1814-4d1d-8d99-a6ca359b0231)


Running simulation in ngspice

![ngspice_simul](https://github.com/user-attachments/assets/a775ff56-132b-480b-92c7-e3f6ef2de777)

Calculating Rise time

![risetime](https://github.com/user-attachments/assets/5f39e81c-5edc-419e-b169-84080a1ef19d)

```
Rise time = (2.24448 - 2.18168) ns = 0.0628 ns
```

Calculating Fall time 

![fall_time](https://github.com/user-attachments/assets/d1971811-63fe-4d33-b9b2-1c16bae8b1e6)

```
Fall time = (4.09455 - 4.05226) ns = 0.04229 ns
```

Calculating cell rise delay

![cell_rise_delay](https://github.com/user-attachments/assets/3d1ca5b8-34a8-426b-8dc3-8f9f8e047df4)

```
Cell rise delay = (2.21 - 2.15) ns = 0.06 ns
```

Calculating cell fall delay

![cell_fall_delay](https://github.com/user-attachments/assets/9599844f-4dec-4870-866c-e479ebec1702)

```
Cell fall delay = (4.07696 - 4.05054) ns = 0.02642 ns
```

Lab exercise to fix poly-9 error 

![drc_check](https://github.com/user-attachments/assets/649a2b86-99bc-4dee-b7c7-bd937ca91eac)


## Day - 3

Checking that our inverter is placed properly on the grid

![grid_matching](https://github.com/user-attachments/assets/d575c2b9-622c-47c4-8d49-ba0dae14d6fe)

Including our custom cell in the floorplan

![custom_cell](https://github.com/user-attachments/assets/4b54f35b-f164-4511-a382-06ec99393564)

![custom](https://github.com/user-attachments/assets/3c5045cb-c77f-4d86-8eb6-f03c0cf6a2f9)

Doing STA outside OpenRoad

![sta](https://github.com/user-attachments/assets/fe449856-2f1a-49cc-8d8d-410206bd5f58)

Doing STA using OpenRoad

![openroad_sta](https://github.com/user-attachments/assets/3c24586e-6522-42ba-8630-9610e2f039ae)

Doing Clock tree Synthesis

![cts](https://github.com/user-attachments/assets/77b28b07-307c-47ce-a43b-b6388ba5e7e1)


## Day - 5

Building Power Distribution network 

![genpdn](https://github.com/user-attachments/assets/f23a4197-f7dd-474c-b886-d5a5e8820e6a)

Running Routing using TritonRoute

![rount](https://github.com/user-attachments/assets/a5ebfd19-1b33-4d75-b327-25b35c215cf7)

![routing_drc](https://github.com/user-attachments/assets/031f64ad-c96d-441e-aad5-49ac8ac72737)

Final Layout 🥳🥳🥳

![final layout](https://github.com/user-attachments/assets/cc543364-52a4-4501-b28c-7f26663392f5)

![layout](https://github.com/user-attachments/assets/4aecb4b0-ceb6-4638-bbf2-f7d3e12e7a9f)

![lay](https://github.com/user-attachments/assets/5dfb7674-b93d-4475-8fb4-095c4ffc059f)

## Acknowledgements

I would like to thank Kunal Ghosh Sir and the whole VSD team for this wonderful course. I have learned a lot about the whole RTL to GDSII flow.






