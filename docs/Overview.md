---
layout: default
title: Overview
nav_order: 4
---
# Overview

## Architecture
FactoMES Resource Model considers Equipment, Material and Person as the main resources. 
All the three are aligned with the processes or process groups for defining production steps or formulae. Processes are configured with the manufacturing lines in a defined yet updatable sequence. 
Operation flow utilizes the Line, Process, Equipment relationship along with Material and Person Model to run work orders and complete production. Outcome of each step is logged to the database for review and reporting.

**Top Level Architecture**
{: style="text-align:center;"}

![](../../assets/images/overview/TopLevelArchitecture.png)
{: style="text-align:center;"}

The FactoMES suite is divided into different models. The models are :
* Resource Model:

    The Resource Model is a refined framework used to optimize the use of resources in a given operation. The model is designed with the assumption that resources can be categorized into three main components: Equipment, Materials, and Personnel.
    The Equipment component refers to the physical tools and machinery used in a process, such as computers, vehicles, or specialized equipment. The Materials component refers to the raw materials, parts, or finished products used in the process, such as chemicals, steel, or finished goods. The Personnel component refers to the human resources involved in the process, including employees, contractors, or service providers.
    Each component of the Resource Model has a set of properties or attributes that define its characteristics and capabilities. These properties can be used to configure the business logic of a given process or operation, such as determining which equipment is needed for a particular process or which materials are required to produce a specific product.

    ![](../../assets/images/overview/ResourceModel.png)
    {: style="text-align:center;"}

* Equipment:
    The Equipment component refers to the tools and machinery used for performing a process or set of processes for the manufacture of a product. . As such, it is mapped to Process, Material and Person Modules. 
    Equipment components play a vital role in the manufacturing process, and its effectiveness and suitability can significantly impact the quality, efficiency, and cost of production. By mapping it to the other modules involved in the process, manufacturers can ensure that their equipment is optimized for the specific process and materials being used, and that the people operating it are properly trained and equipped to use it safely and effectively.

    ![](../../assets/images/overview/Equipment.png)
    {: style="text-align:center;"}

* Material: 
    Material flow engages with Material Master, Inventory Locations and Material utilization. It is referenced by Operations Definition and Performance Model for tracking availability and consumption

    ![](../../assets/images/overview/Material.png)
    {: style="text-align:center;"}

* Process:
    Resource framework integrates with Process to model all processes along with the Equipment and Line. Process properties are aligned with Equipment properties to maintain consistency. For example, if a process requires a certain type of equipment with specific capabilities, these properties must be reflected in the Process module to ensure consistency. 
    Similarly, the Process module must align with the Line module to ensure that the physical layout of the manufacturing environment is reflected accurately in the process model. This is important because the layout of the environment can affect the flow and efficiency of the manufacturing process.

    ![](../../assets/images/overview/Process.png)
    {: style="text-align:center;"}

* Operation:
    Creation and flow of work orders for shop floor operation is defined and set up in the Operations model. The main objective of this is to ensure that the Equipment, Process, Personnel and Material configuration remains available for processing the factory orders.

    ![](../../assets/images/overview/Operation.png)
    {: style="text-align:center;"}

* Operation Performance / Analytics:
    A performance model is a tool or system used to track production activity and related parameters, such as downtime and material consumption. This model helps organizations monitor the efficiency of their production processes, identify areas for improvement, and make data-driven decisions to optimize production and improve overall performance.

    ![](../../assets/images/overview/OperationPerformance.png)
    {: style="text-align:center;"}