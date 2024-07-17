# WATERVERSE DCAT-AP Catalogue

WATERVERSE Datasets, Entity Data &amp; Data Services **metadata** definitions based on the 
[DCAT-AP standard](https://semiceu.github.io/DCAT-AP/releases/3.0.0/) and 
[Smart Data Models](https://github.com/smart-data-models) data model schemas. 

## DCAT-AP data model

The DCAT-AP standard will be used to define the metadata of different Entities, datasets, and data services, ensuring 
structured and interoperable descriptions for each of them. 

The following is the link to the **DCAT-AP datasets data model**: 

https://github.com/smart-data-models/incubated/blob/master/metadata/schema.json

The following is the link to the **DCAT-AP data services data model**:

https://github.com/smart-data-models/incubated/blob/DCAT-AP/DataService/DataServiceDCAT-AP/schema.json


## Project structure 

The project will be organized into three sections that align with the requirements of WATERVERSE Pilot projects:

-  **DCAT-AP Datasets classes**
-  **DCAT-AP Data Service classes** 
-  **Entity Data**  

For each Dataset and Data Service, there will be a folder per pilot where the corresponding description of the metadata 
is provided following the **DCAT-AP** specification.  

# DCAT-AP Dataset classes

## Cyprus Pilot

| Dataset name  |  Metadata URL | 
|-----------|----------------|
| **WATERVERSE_PilotCY_SCADA_ConsumerReports_V0.1** | [Link](Datasets/Cyprus_Pilot/WATERVERSE_PilotCY_SCADA_ConsumerReports_V0.1_metadata.json)| 
| **WATERVERSE_PilotCY_Sensing_SateliteEOData_V0.1**  | [Link](Datasets/Cyprus_Pilot/WATERVERSE_PilotCY_Sensing_SateliteEOData_V0.1_metadata.json) | 
| **WATERVERSE_PilotCY_SCADA_DistrictMeteringAreaData_V0.1**  | [Link](Datasets/Cyprus_Pilot/WATERVERSE_PilotCY_SCADA_DistrictMeteringAreaData_V0.1_metadata.json) | 
| **WATERVERSE_PilotCY_SCADA_SmartMeteringWaterConsumptionDemands_V0.1**  | [Link](Datasets/Cyprus_Pilot/WATERVERSE_PilotCY_SCADA_SmartMeteringWaterConsumptionDemands_V0.1_metadata.json) | 

## German Pilot

| Dataset name    | Metadata URL | 
|-----------|----------------|
| **Nira data**    |  [Link](Datasets/German_Pilot/nira_data_metadata.json) | 
| **Etteln data**    |  Private | 


## Finnish Pilot

| Dataset name    | Metadata URL | 
|-----------|----------------|
| **Clusterability**    |  [Link](Datasets/Finnish_Pilot/clusterability_metadata.json)| 


## Netherlands Pilot

| Dataset name    | Metadata URL | 
|-----------|---------------|
| **KNMI Data (Weather related)**    | [Link](Datasets/Netherlands_Pilot/knmi_observation_metadata.json) | 
| **RWS Data (water quality)**   | [Link](Datasets/Netherlands_Pilot/rws_data_metadata.json)| 
| **Chloride Predictions (from a deployed model)** | Private     | 

## Spanish Pilot

| Dataset name    | Metadata URL | 
|-----------|----------------|
| No Data    |  [Link]         | 

## UK Pilot

| Dataset name    | Metadata URL | 
|-----------|---------------|
| **Environment_agency_data_river**    | [Link](Datasets/UK_Pilot/environment_agency_data_river_metadata.json) | 
| **Environment_agency_data**   | [Link](Datasets/UK_Pilot/environment_agency_data_metadata.json) | 
| **Eater_quality_observation_meteor_cloud** | [Private](Datasets/UK_Pilot/water_quality_observation_meteor_cloud_metadata.json) | 

# DCAT-AP Data Service classes

## German Pilot 

| Entity name    | Data Service URL | 
|-----------|----------------|
| **Flood prediction service**    |  [Link](https://github.com/WATERVERSE/WATERVERSE-DCAT-AP-Catalogue/tree/main/DataServices/German_Pilot/floodPredictionService.jsonld)     | 

## Netherlands Pilot 

| Entity name    | Data Service URL | 
|-----------|----------------|
| **Chloride prediction service**    |  [Link](https://github.com/WATERVERSE/WATERVERSE-DCAT-AP-Catalogue/tree/main/DataServices/Netherlands_Pilot/chloridePredictionService.jsonld)     | 

# Entity Data Catalogue

## Cyprus Pilot 

| Entity name    | Data Model URL | 
|-----------|----------------|
| **Consumer Reports**    |  [Link](https://github.com/smart-data-models/dataModel.WaterConsumption/tree/master/WaterConsumptionObserved)    | 

## German Pilot 

| Entity name    | Data Model URL | 
|-----------|----------------|
| **Rain gauge observations**    |  [Link](https://github.com/smart-data-models/dataModel.Environment/tree/master/WaterObserved)     | 
| **River level observations**    |  [Link](https://github.com/smart-data-models/dataModel.Environment/tree/master/WaterObserved)     | 
| **Soil moisture**    |  [Link](https://github.com/smart-data-models/dataModel.Agrifood/tree/master/AgriSoil)   | 
| **Groundwater level**    |  [Link](https://github.com/smart-data-models/dataModel.Environment/tree/master/PhreaticObserved)   | 
| **Flood Model Data**    |  [Link](https://github.com/smart-data-models/dataModel.Environment/tree/master/FloodMonitoring)   | 

## Finnish Pilot 

| Entity name    | Data Model URL | 
|-----------|----------------|
| **No data model**    |  [Link]     | 


## Netherlands Pilot 

| Entity name    | Data Model URL | 
|-----------|----------------|
| **Water quality observation**    |  [Link](https://github.com/smart-data-models/dataModel.WaterQuality/tree/master/WaterQualityObserved)     | 
| **Water quantity observations**    |  [Link](https://github.com/smart-data-models/dataModel.WaterConsumption/tree/master/WaterConsumptionObserved)   | 
| **Weather Observations (Rainfall, Wind Direction, Wind Speed, Evaporation)**    |  [Link](https://github.com/smart-data-models/dataModel.Weather/tree/master/WeatherObserved)   | 
| **Water quality predictions**    |  [Link](https://github.com/smart-data-models/dataModel.WaterQuality/tree/master/WaterQualityPredicted)   | 

## Spanish Pilot 

| Entity name    | Data Model URL | 
|-----------|----------------|
| **No data model**    |  [Link]     | 


## UK Pilot 

| Entity name    | Data Model URL | 
|-----------|----------------|
| **environment_agency_data**    |  [Link](https://github.com/smart-data-models/dataModel.Environment/tree/master/EnvironmentObserved)     | 
| **water_quality_observation_meteor_cloud**    |  [Link](https://github.com/smart-data-models/dataModel.WaterQuality/tree/master/WaterQualityObserved)    | 


# License

These scripts are licensed under Apache License 2.0.

