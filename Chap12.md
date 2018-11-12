# Floorplan Design for Modern FPGAs
## Outline
* Introduction 
* Algorithm
* Compaction & Postprocessing
* Experimental results

## Why FPGA Floorplaning?
* Floorplaning enbles
	* a divide-and-conquer approach to the physicla implementation
of large designs
	* parallel compilation
* Floorplaning is also a required step in partial
reconfiguration design flow

## FPGA Architecture

## FPGA Floorplaning
* Place a set of modules onto an FPGA chip.
* Resource requirement vector of a module <n_1, n_2, n_3>
	* n_1 is the number of CLBs
	* n_2 is the number of RAMs
	* n_3 is the number of MUXs
* Place eacho module in a rectangular region
satisfying its resource requirement.
* No overlapping among modules.

## Slicing Floorplan

## Module Realizations
* Employ a coordinate system on the chip.
* A realization $r$ for a module $\theta$ is a rectangular
region <x, y, w, h>
	* (x, y) is the coordinate or $r$'s lower left corner.
	* w is the width of $r$.
	* h is the height of $r$.
	* $r$ satisfies the resource requirement of $\theta$.

---
---

## Characteristics of FPGA floorplanning
* heterogeneous resouces
* fixed outline 
* fixed distrucution of resouces
* modules can be placed anywhere
and have no fixed shapes but
must satisfy
the resource requirment of each module

## Some basic question
1. How to represent a floorplan?
2. How can we efficiently idnetify rectangular region
fit for a module?
 
