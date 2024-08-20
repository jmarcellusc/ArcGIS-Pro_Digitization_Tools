# ArcGIS Pro Digitization Tools - 
## Introduction

**Updates**: As of June 2024; I will start revising some script tools for ESRI's ArcGIS Pro. The major reason is code improvement and ESRI's introduction to Apache Engine (they also made changes with some of their libraries).


* **Geographic Data Tools.Zip** - Contains an ESRI Toolbox (Updated August 2024)
	* Attribute Tools (Toolset)
 		* Class Inspector
   		* Numeric Increment Tool
   		* Text Correction Tool 
	* Geospatial Tools (Toolset)
 		* Map Neatline Creator

**NEW**: A cartographic neatline tool will be introduced, this to make cartographic map neatlines more correct and exact based on what I've seen with the USGS. My old and current tool works but requires improvement in corner point entry.

**PURPOSE**: Collection to aid and improve geospatial digitization applications. Made for ESRI's ArcGIS Pro as python scripts, utilizing various libraries to include *arcpy*. Create by <j.marcel.c>. Currently adding various other tools.

## Code Standard
The code in the toolkit is locked to protect the integrity and functionality of the tool. By ensuring that the core code remains unchanged, we can provide a consistent and reliable experience for all users. Locking the code helps prevent unauthorized modifications that could introduce errors or compromise the tool's effectiveness.

However, we understand the importance of transparency and collaboration. Therefore, the code is available upon request. This approach allows us to maintain the tool's integrity while also supporting the needs of users who may wish to review, learn from, or customize the code for their specific purposes. By controlling the distribution of the code, we can also provide support and ensure that any modifications are made responsibly.


## ESRI Tools
### List Notes:
Tools currently completed and available in the ESRI Tool kit. While tested, if any issue or error arises, please contact me to fix any problems. 
#### * Attribute Tools*
	* Class Inspector - Version 2.0
 	* Numeric Increment Tool - Version 1.1
  	* Text Correction Tool - Version 3.0
#### * Geospatial Tools
	* Map Neatline Creator - Version 2.0

### Class Inspector 
Version 2.0: Tool checks each entry for leading, trailing spaces as well for empty and single space entries in all transferable datatypes to a string. It also includes an optional check for NULL values.

### Numeric Increment Tool
Version 1.1: Runs an numeric increment on a single attribute field (either table or feature class). Options include appending a prefix or suffix, modifying the start value, applying a multiplier to the increment, and applying a padding format. Please see 'Use Limitations' for rules.

### Text Correction Tool
Version 3.0: Efficiently modifies text attributes within a single field. Easily adjust letter case, replace empty or null values with customizable options.

### Map Neatline Creator
Version 2.0: Creates correct map neat-lines or vertical/horizontal interval lines correct to the direction of coordinates. NOTE: Will not work across Prime Meridian, Antemeridian, and the Equator.

### Updating Tools -
Tools that are built but required coding updating. These will be added to the ESRI Tool Kit.
* Line Quality Control
* Polygon Quality Control
* Database Spell Check 
* LIAGRE Toolset*
* ~~Field Text Inspector~~
* ~~Field Text Modifier~~
* Line Property Extraction
* Map Unit ***GeMS*** Assembler Quality Control (*GeMS* is a USGS Implementation)
* Editor Tracker Updater
* Image Color Extraction

### Implementing Tools - 
Tools that are in production but require extensive testing and modifications.
* Image Analysis (various)
* PDF OCR
* Point Property Extraction

## Tags
#ESRI, #ArcGIS #Pro #Digitization #Attribution #Neatline #Increment #GIS 

