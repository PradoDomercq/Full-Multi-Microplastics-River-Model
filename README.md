# Full-Multi-Microplastics-River-Model

Microplastics River Model from Nano2Plast project

This repository contains one of the models developed in the ECO48-Nano2plast Project: EXTENDING NANOPARTICLE MODELS TO OPEN SOURCE MODELS OF THE FATE AND TRANSPORT OF MICROPLASTIC IN AQUATIC SYSTEMS.

The Full Multi Team: Proff. Matthew MacLeod (@MacLeodMatt), Dr. Antonia Praetorius (@apraetorius) and Maria del Prado Domercq (@PradoDomercq)

The code contained in this repository is intended as a framework to study microplastics fate and transport along a generic river system.

The model can be parameterised for different microplastic types (composition, shape, size, etc.) and river characteristics (flow velocity, suspended particulates, dimensions, etc.). Furthermore, this framework is intended as a  flexible tool where new or updated fate processes can be included or reparameterised easily. 

This model follows a modular multimedia mass-balance modelling approach in which a system of coupled mass balance equations is built describing the transformation and transport processes of the plastic particles within the modelled system with specific rate constants. 

The modelled system consists of a generic one directional river structure where the river is subdivided in a set of river sections (RS) connected horizontally. Each river section is, at the same time, subdivided into four compartments of different types and dimensions representing a surface water layer (w0), a flowing water body (w1), a stagnant water body compartment (w2) and the top sediment layer of the river bed (sed). The system of differential equations is parameterized according to each compartment properties and dimensions and solved in a dynamic mode so that it yields the particles’s concentration (in number or mass per volume) in each river section and compartment as a function of time.

![Alt text](https://github.com/PradoDomercq/Nano2Plast_RiverModel/blob/main/FigureGenericRiver.png "Generic River")


OPEN SOURCE CODE WILL BE AVAILABLE SOON!

For an early invitation to the repository contact prado.domercq@aces.su.se by providing your GitHub userame

