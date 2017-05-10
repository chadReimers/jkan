---
schema: default
title: XL Dataset 40 tables loaded into (CDS) dataset
organization: XL
notes: This is a partial XL CDS Data store
resources:
  - name: Air Monitoring Stations CSV
    url: 'http://data.phl.opendata.arcgis.com/datasets/1839b35258604422b0b520cbb668df0d_0.csv'
    format: csv
  - name: Air Monitoring Stations Shapefile
    url: 'http://data.phl.opendata.arcgis.com/datasets/1839b35258604422b0b520cbb668df0d_0.zip'
    format: shp
  - name: Air Monitoring Stations GeoService
    url: 'https://services.arcgis.com/fLeGjb7u4uXqeF9q/arcgis/rest/services/Air_Monitoring_Stations/FeatureServer/0/query'
    format: api
license: 'https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/'
NRT Vs Batch:
  - Batch replication
ETL Vs Activity:
  - ETL 
Refresh Rate:
  - Daily
Relative data size:
  - 30 TB
Environment / tech stack:
  - SQL Server
Loaded into the cloud or. virtual access
  - Cloud based and available in BOS03
Accessible from the following:
  - Athena
category:
  - Education
maintainer: Chad 
maintainer_email: 
---
