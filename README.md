# Vertical Farming Ontology
The current ontology represents vertical farming examply for Ambient intelligence exercise II. The application is built using [Protegé](https://protege.stanford.edu/) software. 


**Author**: *[Bauyrzhan Zhakanov](https://github.com/bzwayne)*, [s5218116@studenti.unige.it](s5218116@studenti.unige.it)

**Course Instructors**: *[Antonio Sgorbissa](https://rubrica.unige.it/personale/UkNHWlJp)*


# A brief introduction to Vertical Farming
A Vertical farming is a technology that allows to harvest the plants. This technology could be usefull for the land, where the land is not suitable for agriculture. For example: mountains, rocky places or cold places. Using this technology, we could use water more effiently, avoid land degrading, provide more effient yield and etc. Vertical Farming is built using **Entities, data properties, object properties and SWRL rules**, and its reasoner used **Pellet**.

## Entities
The list of classes of sub-classes used in Vertical Farming Ontology:
  * VerticalFarming: A vertical farming
  * Mode: Vertical Farming mode
  * Time: A time of the day
  * Plant: is a plant
  * PlantCondition: A plant condition: ready or not ready to pick
  * Sensors: A set of sensors: humiditySensor, temperatureSensor, lightSensor
  * Control: The activity that will be used to control plant grow by using SWRL.

<!-- ![image](https://user-images.githubusercontent.com/91313196/205524606-5062736b-6ab4-4b2c-a849-3e295b1579b7.png) -->

## Object Properties
 - hasPlant: a Vertical Farming hasPlant Plant
 - isReady: Plant isReady PlantCondition.
 - hasSensor: VerticalFarming hasSensor Sensors
 - inMode: VerticalFarming is inMode Mod

<!-- ![image](https://user-images.githubusercontent.com/91313196/205525087-76ce391b-155a-411e-86fd-41b3e8168af5.png) -->

## Data Properties 
 * hasTemperature: The temperature of the Vertical Farming (string) to the temperature sensor 
 * hasHumidity: The humidity of the Vertical Farming (string) to the humidity sensor 
 * hasTime: Assigns a time (string) to the Day Time for Light turned On

<!-- ![image](https://user-images.githubusercontent.com/91313196/205525180-f35ed120-fb79-4ee0-aa56-989a9fd3f895.png) -->

##SWRL rules 

<!-- ![image](https://user-images.githubusercontent.com/91313196/205525190-59820b71-7c8d-4572-b299-499b9739e759.png)

    

  


