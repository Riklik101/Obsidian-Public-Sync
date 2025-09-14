In it's most simplest form, a nuclear reactor uses [[Uranium]] and other radioactive materials and the fission from uranium to create heat, and transfer that heat into steam to create power. Nuclear reactors are one of the biggest sources of energy, although not renewable, uranium has a very high energy density resulting in massive power transmissions. 

There are many different types of nuclear reactors, and this term serves as a broad hub/introduction for each type. 

After uranium is used in reactors, it is termed [[Spent Nuclear Fuel]]. In many [[Thermal Reactor]]s, this spent fuel is stored in [[Spent Fuel Pool]]s, and it can later go under reprocessing.

Table of Contents:
* Reactor Operation
	* Startup
	* Operations
	* Shutdown
	* Fuel
	* Cooling
* Types of Reactors
	* BWR, EPR, VVER, PWR, FNR
# Reactor Operation
Due to the various types of reactors, I will be assuming a generalized reactor for simplicity.
### Startup
In order to produce heat from a reactor, the nuclear fuel contained within must achieve [[Criticality]]. Operators pull [[Control Rods]] from the reactor. These rods contain boron, which absorbs the neutrons from the enriched uranium fuel. When these rods are pulled, the neutrons from uranium can impact each other and create a fissile reaction, that is eventually self sustaining. When it reaches this point, the reactor has achieved criticality. 
### Operation
Once the reactor achieves criticality, the water or other moderator within the fuel rods structure can boil, producing steam. This steam is the main source of power, as it can be fed into another heated loop, or directly to spin turbines and create electricity. At this point, the task is to keep the reactor at a stable power mode.
* Recirculation pumps within the reactor pressure vessel can be used to collapse steam voids and maintain criticality and stable power
* CST pumps can be used to refill the loops in the event of a small leak or loss of water in some way
* Pressure control systems to ensure the pressure of the water and steam does not exceed rated boundaries
* Radiation monitoring and sensors to control fine details
When enough pressure is built in the reactor, turbines can be spun up and synced to the power grid, producing electricity for it. 

### Shutdown
Basically startup in reverse.
## Fuel
Reactors use fuel[^1]. Specifically, [[Uranium]] is used. (in most cases). After multiple rounds of fission has occurred, uranium reaches its end of life. This is either by it being unable to sustain a proficient enough nuclear reaction to generate heat, or that it is simply too depleted or other reasons. In this case, it is now referred to as [[Spent Nuclear Fuel]], and is often stored in a [[Spent Fuel Pool]] before eventually being stored in dry casks or other [[Nuclear Waste Disposal]] Methods.

Fuel is contained inside of [[Fuel Rods]], which contain [[Zirconium]] [[reactor cladding]], which provides a major benefit to the thermal efficency of these rods.

For a sustained reaction, control methods are needed. In this case, [[Control Rods]] are used, using a [[Control Rod Drive]] subsystem. In BWR reactors, control rods are fed through bottom penetrations in the [[RPV|Reactor Pressure Vessel]], and as such, require other equipment, unlike PWRs and other such reactors where gravity can be used as an assist mechanism. 
## Cooling
Reactors need cooling[^2]. Primary cooling is usually the same way that we extract power, cycling water through the reactor core, then heat exchangers to extract the heat in the case of a PWR or directly use steam from the core in a BWR, and then a [[Condenser]] to return the steam into water that can be heated again. These cooling methods are generally enough to manage the cooling the reactor needs. If the reactor experiences an emergency, [[ECCS|Emergency Core Cooling Systems]] can be utilized to ensure safety.


# Types of Reactors
## Thermal Reactors
Thermal reactors are reactors specifically designed to be energy producing - neutrons are given from uranium rods of varying enrichment, and [[Light Water]] is generally used as a coolant and moderator which allows fission to occur, generating heat and therefore power. 
### Pressurized Water Reactor
A [[PWR reactor]] is the most common type of reactor. The water in this type of reactor is pressurized, so that water can be used as coolant; the boiling point of water increases as it's pressure increases. In this type, there are two loops of water: hot water flowing through the [[RPV]] and the water that turns into steam and spins the turbine; this water meets the RPV water through a heat exchanger. Since water remains a liquid throughout operation, control rods can be placed at the top, allowing for maximum safety during plant transients. 
#### European Pressurized Reactor
The [[EPR Reactor]] is a PWR-type reactor designed by [[Framatone]], designed to be more economically competitive. 

#### VVER Reactor
The [[VVER Reactor (WWER)]] is a [[Soviet Union]] designed reactor, of the PWR type. The distinguishing factor for this reactor is that it has horizontal steam generation and hexagonal fuel assemblies. 

### Boiling Water Reactor
A [[BWR reactor]] is the second most common type of reactor. In this reactor, water directly goes throughout the plant as it heats into steam, that is used to spin turbines for electricity. Since water stays throughout the plant in one coolant loop, control rods are placed at the bottom - as steam goes into the top of the RPV. Control rods placement at the top requires a specialized [[Control Rod Drive]] system to be used. This is because gravity cannot help in a scram: some type of power is necessary to move the reactors rods in both positioning and emergency events. 

An interesting side note is that since there is only one coolant loop, radioactive water is present everywhere in the plant, meaning that if the turbines or any other place experience a leak, it is almost certainly the release of radioactive water. (Excluding some subsystems present in every plant)

## Fast Neutron Reactors
[[Fast Neutron Reactor]]s have an excess of neutrons, requiring an higher enrichment of uranium. In this type, water is not used as a moderator and different types of coolants can be used. This type is not very common, however. 



[^1]: Citation needed
[^2]: Citation needed
