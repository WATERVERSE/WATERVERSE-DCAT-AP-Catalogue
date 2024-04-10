# WATERVERSE-DCAT-AP-Catalogue

WATERVERSE Datasets, Entity Data &amp; Data Services **metadata** definitions based on the **DACAT-AP** standard. 

# Datasets Catalogue 

## CY Pilot

| Dataset name  |  Metadata URL | 
|-----------|----------------|
| **Consumer Reports**    | [Link]         | 
| **Satelite Data**   | [Link]         | 
| **(SCADA) Telemetry Data**  | [Link]     | 
| **Water Consumption Demands**  | [Link]     | 

## DE Pilot

| Dataset name    | Metadata URL | 
|-----------|----------------|
| **Nira data**    |  [Link]     | 
| **Etteln data**    |  Private    | 


## FI Pilot

| Dataset name    | Metadata URL | 
|-----------|----------------|
| **Clusterability**    |  [Link]         | 


## NL Pilot

| Dataset name    | Metadata URL | 
|-----------|---------------|
| **KNMI Data (Weather related)**    | [Link]         | 
| **RWS Data (water quality)**   | [Link]         | 
| **Chloride Predictions (from a deployed model)** | Private     | 
| **Water Consumption Demands** |  [Link]     |

## SP Pilot

| Dataset name    | Metadata URL | 
|-----------|----------------|
| No Data    |  [Link]         | 

## UK Pilot

| Dataset name    | Metadata URL | 
|-----------|---------------|
| **Environment_agency_data_river**    | [Link]         | 
| **Environment_agency_data**   | [Link]         | 
| **Eater_quality_observation_meteor_cloud** | Private     | 

# Entity Data Catalogue

## CY Pilot 

| Entity name    | Data Model URL | 
|-----------|----------------|
| **Consumer Reports**    |  [Link](https://github.com/smart-data-models/dataModel.Weather/tree/master/WeatherAlert)    | 
| **Smart Metering Data**    |  [Link](https://github.com/smart-data-models/dataModel.Energy)  | 

## DE Pilot 

| Entity name    | Data Model URL | 
|-----------|----------------|
| **Rain gauge observations**    |  [Link](https://github.com/smart-data-models/dataModel.Environment/tree/master/WaterObserved)     | 
| **River level observations**    |  [Link](https://github.com/smart-data-models/dataModel.Environment/tree/master/WaterObserved)     | 
| **Soil moisture**    |  [Link](https://github.com/smart-data-models/dataModel.Agrifood/tree/master/AgriSoil)   | 
| **Groundwater level**    |  [Link](https://github.com/smart-data-models/dataModel.Water)   | 
| **Flood Model Data**    |  [Link](https://github.com/smart-data-models/dataModel.Environment/tree/master/FloodMonitoring)   | 

## FI Pilot 

| Entity name    | Data Model URL | 
|-----------|----------------|
| **No data model**    |  [Link]     | 


## NL Pilot 

| Entity name    | Data Model URL | 
|-----------|----------------|
| **Water quality observation**    |  [Link](https://github.com/smart-data-models/dataModel.WaterQuality)     | 
| **Water quantity observations**    |  [Link](https://github.com/smart-data-models/dataModel.WaterConsumption/tree/master/WaterConsumptionObserved)   | 
| **Weather Observations (Rainfall, Wind Direction, Wind Speed, Evaporation)**    |  [Link](https://github.com/smart-data-models/dataModel.Weather/tree/master/WeatherObserved)   | 
| **Water quality predictions**    |  [Link](https://github.com/smart-data-models/dataModel.WaterQuality)   | 

## SP Pilot 

| Entity name    | Data Model URL | 
|-----------|----------------|
| **No data model**    |  [Link]     | 


## UK Pilot 

| Entity name    | Data Model URL | 
|-----------|----------------|
| **environment_agency_data_river**    |  [Link](https://github.com/smart-data-models/dataModel.Environment)     | 
| **water_quality_observation_meteor_cloud**    |  [Link](https://github.com/smart-data-models/dataModel.WaterQuality)    | 



# DCAT-AP data model

The DCAT-AP standard will be used to define the metadata of different Entities, datasets, and data services, ensuring structured and interoperable descriptions for each of them. 

Link to the DCAT-AP datamodel: 
https://github.com/smart-data-models/incubated/blob/master/metadata/schema.json

# Project structure 

The project will be organized into three folders that align with the requirements of WATERVERSE Pilot projects:

-  **Datasets**
-  **Entity Data**  
-  **Data Services** 

For each Datasets, Entity Data &amp; Data Services, there will be two folders per pilot corresponding to:
-  The repository of the corresponding **Data Model**. 
-  A json file of the metadata based on the **DCAT-AP** specification.  

# License

These scripts are licensed under Apache License 2.0.

