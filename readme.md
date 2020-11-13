# Welcome to the EDDB Database aggregation and visualization Project #

This is in fullfillment of a project for CS 523(Topics in Database Systems) at Western Illinois University

## Project Overview ##

### The Data ###
The data for this project is from an MMO called Elite Dangerous (ED). ED takes place in the vastness of space where players are free to do whatever they want within the confines of the game mechanics such as: trading, becoming a space pirate, astroid mining and much more. 

The game is proceduarally generated. When a player 'jumps' to a new system, one will be created using space math that is beyond me. This means the game is somewhat infinite. 

![Two System Spheres: Nerthus and Sol](https://github.com/JacobLD/EDDB/blob/master/Img/sol_nerthus.PNG)

The files used to construct the databases were pulled from [here](https://eddb.io/api). The data is updated daily when the official EDDB does its nightly data dump. If you want to recreate the results found in this project you can download the files we used [here](https://drive.google.com/file/d/1vBIUQmErZzgLlenMJXuB4oJvEPDopNGg/view?usp=sharing). To replicate simply extract the 'Data' folder into the root of the project and go from there.

![All Systems](https://github.com/JacobLD/EDDB/blob/master/Img/all_systems.PNG)

The systems file contains all the populated systems in ED. There are over 20,000 and can be seen grouped in a long arm cluster. These are the only systems we care for because these are the systems that involve commerce!

Within each system is one or more stations. Stations are hubs dedicated to landing space crafts and spending space credits on various goods. A player can buy commodities to do trading in addition to buying modules for their ship and even new ship if they have enough credits.  

# Project Goals #
* Implement similar data across multiple database systems
    - [ ] MongoDB
    - [x] Neo4j
    - [ ] MariaDB
* Optimize similar queries for all of those databases.
    - [ ] Count how many systems each faction controls.
    - [ ] Return the commodity with the highest profit margin.
    - [ ] Retrun the system that sells a given commodity for the lowest price.
    - [ ] Retrun the system that buys a given commodity for the highest price.
    - [ ] Given a system and a range, find the best commodity to buy and sell locally.
    - [ ] Locate the nearest system that provides certain services.
    - [ ] Locate nearest station with a black market.
    - [ ] Return the rarest module and where to buy it.
    - [ ] Find the best path between two systems given the jump range of a ship.
    - [ ] Build aggregation of listings data to display, average cost of a given item, total supply, total demand, etc.


## Results ##

### Query Comparisons ###
TBD

## Closing Notes ##
TBD
