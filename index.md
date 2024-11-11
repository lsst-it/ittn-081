# Summit Computer Room Cooling System

```{abstract}
Describes cooling system of the computer room and plans for a backup line. 
```

## Introduction

The HVAC system is a critical component in maintaining optimal environmental conditions in the computer room.

The following is a summary of the current state of the cooling lines to the computer room, and plans for the installation of a new backup line.

## Current State

The cooling system for the computer room is connected to Chiller 3, located on the first floor of the building.

![First Floor](./images/first_floor.jpg "First Floor")

This Chiller supplies the CRAC units within the computer room. The lines connected to this Chiller are mixed with 35% glycol, which allows for optimal cooling efficiency and freeze protection. Glycol is essential in this setup as it prevents the coolant from freezing at low temperatures, especially during colder months. This antifreeze characteristic of glycol helps maintain consistent temperatures, reduces the risk of pipe damage due to freezing.

The lines supplying the CRAC units are installed within the false ceiling of the second floor, and the return lines interconnect above the location of the bathrooms.

![Current Lines](./images/current_lines.jpg "Current lines")

There's a backup line connected to Chillers 1 and 2, which, through a heat exchanger, can supply the CRAC units in case of an issue with Chiller 3, however a second backup is in the planning, connected to a different UPS that could provide cooling in the case when the main UPS fails.

## Planned State

To improve the availability of the CRAC units in the computer room, a second backup line from the Coating chiller will be connected to the main supply line that serves the computer room. This additional backup connection will enhance system redundancy, providing an extra layer of reliability in case of any disruptions with the primary or existing backup chillers

The Coating chiller has 2 lines isolated from each other. One with 25% glycol and the other one with 38% glycol. Given the Chiller is currently mixed at 35% glycol, it should be compatible with 38% line coming from the Coating Chiller, which can be reduced to 36%. While this is a 1% reduction in the cooling of the computer room, it is acceptable.

![Chiller Coating](./images/chiller_coating.png "Chiller Coating")

The reduction on glycol mix could potentially free up 50Kw of capacity from the main system which could be good in commissioning

The connection to the current line will be done as shown in the image.

![New Lines](./images/new_lines.jpg "New Lines")

### Considerations

Adding an inline filter near the coating chamber chiller, specifically on the line leading to the computer room, would be beneficial even though the coating chamber already has its own filter.

Installing a check valve can help prevent backflow, providing an additional layer of protection beyond the four motorized valves that will be installed in line with the coating chiller. This check valve will ensure that the coolant flows in only one direction, preventing any potential reverse flow that could modify the glycol mixture.

### Controls

To ensure the correct functioning of the system, the following controls must be implemented:

- Monthly checks should be conducted, with the system running continuously for several days to ensure proper flow.

- Glycol concentration checks to maintain the expected mixture on both lines in the Coating chiller

- Regularly test the redundancy and switchover process of the backup systems to ensure they function seamlessly in an emergency.
