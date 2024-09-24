# Table of contents : 
* Know Data Attributes
* Ask Questions
* Assessing Data
* Clean Column Labels 
* Filter, Drop Nulls, Dedupe
* Inspect Data Types
* Fixing Data Types
* Exploring with Visuals
* Merge Datasets 
* Results with Merged Datasets 


# What is Fuel Economy?
Fuel economy refers to the efficiency of a vehicle in using fuel, typically measured by the distance a vehicle can travel per unit of fuel. It is most commonly expressed in terms of miles per gallon (MPG) in countries using the imperial system, or kilometers per liter (km/L) in countries using the metric system. Fuel economy indicates how efficiently a vehicle converts fuel into motion, impacting both the operating cost and environmental footprint of the vehicle.

Higher fuel economy means a vehicle can travel farther on less fuel, which is more cost-effective and environmentally friendly, as it reduces fuel consumption and emissions. Factors affecting fuel economy include engine efficiency, vehicle weight, aerodynamics, driving habits, and road conditions..

# Data set :
Fuel Economy Data
This information is provided by the U.S. Environmental Protection Agency, Office of Mobile Sources, National Vehicle and Fuel Emissions Laboratory.
Note that the datasets we'll be working with are slightly simpler than those found through the links below.
* EPA Fuel Economy Testing : https://www.epa.gov/compliance-and-fuel-economy-data/data-cars-used-testing-fuel-economy
* DOE Fuel Economy Data : https://www.fueleconomy.gov/feg/download.shtml/
For better understanding of the dataset, you can refer the Green Vehicle Guide Documentation and data description. 

# Attribute	Description : 
* Model	Vehicle make and model
* Displ	Engine displacement - the size of an engine in liters
* Cyl	The number of cylinders in a particular engine
* Trans	Transmission Type and Number of Gears
* Drive	Drive axle type (2WD = 2-wheel drive, 4WD = 4-wheel/all-wheel drive)
* Fuel	Fuel Type
* Cert Region*	Certification Region Code
* Sales Area**	Certification Region Code
* Stnd	Vehicle emissions standard code (View Vehicle Emissions Standards https://www.epa.gov/greenvehicles/federal-and-california-light-duty-vehicle-emissions-standards-air-pollutants)
* Stnd Description*	Vehicle emissions standard description
* Underhood ID	This is a 12-digit ID number that can be found on the underhood emission label of every vehicle. It's required by the EPA to designate its "test group" or "engine family." This is explained more here https://www.epa.gov/vehicle-and-engine-certification/information-about-family-naming-conventions-vehicles-and-engines
* Veh Class	EPA Vehicle Class
* Air Pollution Score	Air pollution score (smog rating)
* City MPG	Estimated city mpg (miles/gallon)
* Hwy MPG	Estimated highway mpg (miles/gallon)
* Cmb MPG	Estimated combined mpg (miles/gallon)
* Greenhouse Gas Score	Greenhouse gas rating
* SmartWay	Yes, No, or Elite
* Comb CO2*	Combined city/highway CO2 tailpipe emissions in grams per mile

"*"  means  Not included in 2008 dataset
"**"  means Not included in 2018 dataset



