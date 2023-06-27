# Seismic Hazard - Local Soil Conditions
<p align="justify">
This Earthquake – or seismic hazard – layer is a global map of Peak Ground Acceleration (PGA) in units of g, considering local site conditions (i.e. the local geology of the site) at 200-meters spatial resolution, allowing a more specific site risk assessment. As an example, urban areas often lie on top of soft sediments, a geologic domain more prone to experience amplification of seismic waves. This phenomenon is considered in this new layer.
</p>

# Layer Description
<p align="justify">
Site response – as a consequence of local site conditions – describes the amplification of seismic waves (i.e. ground motion) in presence of soft sediments. While this is a key aspect of hazard assessment and risk models, it is not reflected in standard seismic hazard maps, which depict ground motion on reference site conditions(bedrock). This layer is a seismic hazard  map  at  local site  conditions,  depicting  the geographic  distribution  of  the Peak Ground Acceleration (PGA) with a 10% probability of being exceeded in 50 years(475-year return period,  RP).The layer  is  an  addition  to  the Earthquake hazard  layer version  2018.1 on reference  site conditions (shear wave velocity, Vs30, of 760-800 m/s).  
</p>

# Provided Attributes

Attribute | Description | Example |
--- | --- | --- | 
Category|Classified Peak Ground Acceleration [g] values, amplified following the developed regional amplification rules for Vs30 soil classes|Significant (0.161-0.29)|
Modified Mercalli Intensity (MMI)|Roman numerals from I (low) to   X (high), not mathematically based; instead, it is an arbitrary ranking based on observed effects. The   Modified Mercalli Intensity value assigned to a specific site after an earthquake is a more meaningful measure of severity to many  people that is magnitude,  because intensity refers to the effects actually experienced at that place|VII|
Peak Ground Acceleration [g]|Peak Ground Acceleration (PGA) with a 10% probability of being exceeded in 50 years (=475y return period), computed for local soil conditions (from average shear wave velocity in the upper 30m, Vs30, in m/s)|0.217|
People's Reaction|Qualitative value describing the   Modified Mercalli Intensity (Figure below)|Frightens most and some lose balance|
Furnishings|Qualitative value describing the   Modified Mercalli Intensity (Figure below)|Heavy furniture overturned|
Built Environment|Qualitative value describing the Modified Mercalli Intensity (Figure below)|Damage negligible in buildings of good design and construction, but considerable in some poorly built or badly designed structures; weak chimneys broken at roof line, unbraced parapets fall|
Natural Environment|Qualitative value describing the Modified Mercalli Intensity (Figure below)|Tree damage, rockfalls, landslides, and liquefaction are more severe and widespread with increasing intensity|
Intensity Value|Intensity value = LOG10(PGA g /0.0275)/LOG10(1/0.0275)*10 If PGA g is less than 0.0275 then intensity is 1. If PGA g is greater than 1 then intensity is 10. For a comparison between different hazards and over time in case of changing information attribute values are mapped to a scale of 1-10 to express very low to extreme hazard, frequency or impact as such. Zero values mean "no data available". While this approach may be oversimplified for some scoring methods, it does eliminate the need for an update of a related interpretation method should the database value change one day.|1|

![image](https://github.com/SwissRe/Seismic_Hazard-Local_Soil_Conditions/assets/83059920/9b3a60fb-6a9c-428d-8995-86a679481ea6)



# Data Sources

Data Source | Link to Data Source | Vintage |
--- | --- | --- | 
Global Earthquake Model (GEM) Hazard Model Mosaic (Pagani et al., 2018)| https://hazard.openquake.org/gem/ | 2018 |
United States Geological Survey (USGS) Shear Wave Velocity in the upper 30m| https://earthquake.usgs.gov/data/vs30/ | 2020 |

# User Agreement/Legal Notice

<p align="justify">
The " Earthquake – Local Soil Conditions " is a layer that shows expected ground motion level at actual local site conditions. It has been calculated based on the GEM2018 bedrock hazard (provided by GEM, available from Global Hazard Map - Global Earthquake Model (https://www.globalquakemodel.org/product/global-hazard-map) under CC BY-SA license and VS30 from slope (provided by USGS, available from https://www.usgs.gov/information-policies-and-instructions/copyrights-and-credits under Public Domain). Earthquake – Local Soil Conditions is provided by Swiss Re and licensed under CC BY-SA 4.0  license (https://creativecommons.org/licenses/by-sa/4.0/legalcode). 
</p>

# Release Date

May 2023
