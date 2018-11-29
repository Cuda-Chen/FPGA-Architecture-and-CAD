# Power Optimization Techniques for FPGAs

## Outline
* Introduction
* Hardware Techniques
* EDA Solutions
* Hardware + EDA

## Introduction
* Power consumption is a key concern today
* Reducing power will 
	* Lower packaging cost and cooling costs
	* Improve reliability
	* Lengthen the battery life of mobile device
* FPGA's programmability incurs extra power overhead in
	* More transistors are needed to omplement a logic
function than custom ASIC
	* Longer wire lengths
	* Inclusion of programmable routing switches

## Power Reduction Techniques
* Combination of techniques to reduce
	* Dynamic power
	* Static power
* Combination of hardware techniques and EDA
solutions.

## Dynamic Power vs Leakage Power
* Two major sources of power dissipation
	* Dynamic power -- caused by signal transition
	* Static (leakage) power -- caused by leakage currents
in off transistors
* Dynamic power: ![Alt Text](pg6.gif)
* Leakage power
	* proportional to transistor count
	* dependent on supply voltage and threshold voltage

---
---

## PPA optimization
* power, performance, area
