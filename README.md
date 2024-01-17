# IOFMaterialsTutorial

# Table of Contents
- [IOFMaterialsTutorial](#iofmaterialstutorial)
- [Table of Contents](#table-of-contents)
- [Basic Tutorial](#basic-tutorial)
  - [Introduction DrawIO and Chowlk](#introduction-drawio-and-chowlk)
  - [Data Conversion](#data-conversion)
  - [Create a Mapping](#create-a-mapping)
  - [Apply Mapping](#apply-mapping)
  - [Load Data](#load-data)
  - [Query Data](#query-data)
- [Advanced Examples](#advanced-examples)
  - [Hardness Measurements](#hardness-measurements)
  - [Image Analysis](#image-analysis)

# Basic Tutorial

## Introduction DrawIO and Chowlk
 - Start DrawIO Session [ClickME](https://app.diagrams.net/)
 - Create a new Blank Diagram and give it a name 
  ```
  LenghtMeasurement.drawio.xml
  ```
 - Install IOF Materials ScratchPad from
  ```
  Url Scatchpad
  ```
 - Create a Simple Graph: Measure the Length of a Object
 - converserion to RDF with [Chowlk](https://chowlk.linkeddata.es/)
## Data Conversion
A simple Measurements Table
  - Create Table with Length consequtive Measurements of the Objects Length
  - Conversion of Table to RDF with [CSVToCSVW](https://chowlk.linkeddata.es/)
## Create a Mapping
Create a Mapping of Graph to Data Table
    - Create a Mapping with [MapToMethod](https://maptomethod.matolab.org/)
## Apply Mapping
Apply Mapping to RDF Data
## Load Data
Load Data to Triplestore
## Query Data
Sample Querys on Create Graph

# Advanced Examples
## Hardness Measurements
Using [HardnessGraph](https://gitlab.com/kupferdigital/process-graphs/vickers-hardness-test-fem)
[Image](https://user-content.gitlab-static.net/e8fcc493e7403be54bcd61c1889d9eb8f191ead4/68747470733a2f2f6b75706665726469676974616c2e6769746c61622e696f2f70726f636573732d6772617068732f7669636b6572732d686172646e6573732d746573742d66656d2f7669636b6572732d686172646e6573732d746573742d66656d2e737667)
## Image Analysis
Using this [Repo](https://github.com/BAMresearch/DF-TEM-PAW/tree/main)
