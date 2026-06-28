# Stubble Burning Hotspot Analysis in Punjab

## Overview

This project analyzes satellite-detected stubble burning incidents across Punjab to understand temporal patterns, fire intensity, and spatial hotspot concentration. The study focuses on identifying peak burning periods and major hotspot districts contributing to seasonal air pollution.

## Problem Statement

Stubble burning is a major environmental challenge in northern India, contributing to air pollution, greenhouse gas emissions, and soil degradation. This analysis explores how and where these burning events are concentrated.

## Dataset

Source: Reap Benefit SamaajData Climate Dataset

Fields used:

* Year
* District
* Date
* Fire Power (W/m²)
* Latitude
* Longitude

## Methodology

### Data Cleaning

* Checked and handled missing values
* Standardized date formats
* Removed duplicate records
* Removed faulty coordinates (same latitude and longitude values)
* Validated spatial extent

### Temporal Analysis

* Monthly distribution of fire events
* Average fire intensity analysis

### Spatial Analysis

* Imported cleaned CSV into QGIS
* Reprojected to UTM Zone 43N
* Generated heatmap for hotspot density visualization
* Validated hotspot districts

## Key Findings

* Most fire incidents occurred in October and November
* November recorded the highest fire intensity
* Major hotspot districts included Sangrur, Bathinda, Firozpur, and Patiala
* Burning patterns are highly seasonal and geographically concentrated

## Tools Used

* Python
* Pandas
* Matplotlib
* QGIS

## Outputs

* Monthly fire occurrence bar chart
* Monthly fire intensity graph
* Spatial hotspot heatmap



