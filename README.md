# README
This script runs a series of get request on a specified FAIR Data Point (FDP).

It uses the Linked Data Platform (LDP, http://www.w3.org/ns/ldp#) ontology defined subclasses within the FDP to drill down the FDP structure until all data is obtained.
The "ignore" tuple at the top of the file contains the resource URLs that should be ignored while exploring the FDP.

## How to use:
Call get_resource function with the URL of your FDP and define the turtle file wherein an aggregated graph of the complete FDP should be stored.
See __main__ of the file for an example.
