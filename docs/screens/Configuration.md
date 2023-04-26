---
layout: default
title: Configuration
parent: Screens
nav_order: 1
---
# Configuration

<!-- In Configuration screen you have the following tabs. -->
A key benefit of FactoMES is the intuitive and structured design of its configuration screens. The screens are organized into tabs or sections, with each tab or section focusing on a specific area of configuration. This approach helps users to quickly navigate through the configuration settings and make changes to the setup parameters and Master Data as needed.

In addition, FactoMES provides clear and concise explanations of each configuration option, making it easy for users to understand the purpose of each setting. This means that even users who are new to the platform can quickly learn how to configure and customize the software to meet their specific needs thereby reducing the risk of errors and mistakes

## Equipment Level
<!-- * Equipment Level screen will help you to maintain Enterprise level master data.
* Properties for this data can be created using below section.
* Site, Area and Production Lines related data can be entered using available tabs. -->
* Equipment screen helps you maintain the consolidated Equipment related information at one place. The equipment is defined at Area Level
* The screen is split into two sections with top section for creation or update of Equipment while the bottom section stores properties or attributes specific to each equipment selected above.
* Remaining tabs in the bottom section are designated for capture and display of the Site, Area and Production Line related data specific to the selected Equipment.

![](../../../assets/images/screens/equipmentlevel.png)
{: style="text-align:center;"}

## Common Lookup
<!-- * Common Lookup screen will help you to create setup parameters which is going to be common across the project.
* There are two types of parameters can be created. First is "Common Lookup Type" and Second is "Common Lookup Code".
* Common Lookup Code is dependent on Common Lookup Type, so, Common Lookup Type needs to be created first. -->
* Common Lookup values are used across the application for common parameters and common tasks. They often appear as drop down list values for other screens 
* It is designed in two parts. There is Common Lookup Type and there are Common Lookup Codes under a Type. 
* Lookup Type is a header value and all Lookup Codes are defined under their specific Headers. Therefore, Common Lookup Type is created first followed by Common Lookup Codes for the Type. 

![](../../../assets/images/screens/commonlookup.png) 
{: style="text-align:center;"}

## Navigation
<!-- * Navigation screen will help you to setup menu for client of the project. You can also set user access level for roles of the users.
* It helps in setting up additional protection besides Ignition's authentication profile. -->
* Function of the Navigation Screen is to help the Super User design the navigation path for individual screens. It also allows the Superuser to maintain access control for other users. 
* With this screen, the administrator can implement additional protection and access control besides Ignition's seeded authentication profile.

![](../../../assets/images/screens/navigation.png) 
{: style="text-align:center;"}


