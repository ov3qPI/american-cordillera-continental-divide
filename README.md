# american-cordillera-continental-divide
GIS polyline of the Continental Divide of the American Cordillera, Alaska to Patagonia, derived from HydroBASINS and national hydrographic data.
## Data sources and provenance
### HydroBASINS / HydroSHEDS version 1 (World Wildlife Fund)
The existing KML identifies HydroBASINS as a source, including its Level-3 boundary limit near 52.76 degrees south. HydroBASINS is part of the HydroSHEDS project developed by World Wildlife Fund (WWF) and collaborators. This repository has not established the precise input HydroBASINS files, versions, or processing commands.
- HydroBASINS product and license: https://www.hydrosheds.org/products/hydrobasins
- HydroSHEDS v1 technical documentation and license (Appendix A; required attribution in Exhibit B): https://data.hydrosheds.org/file/technical-documentation/HydroSHEDS_TechDoc_v1_4.pdf
- HydroBASINS scientific reference: Lehner, B. and Grill, G. (2013). Global river hydrography and network routing: baseline data and new approaches to study the world's large river systems. Hydrological Processes 27(15), 2171-2186. https://doi.org/10.1002/hyp.9740
- HydroSHEDS scientific reference: Lehner, B., Verdin, K. and Jarvis, A. (2008). New global hydrography derived from spaceborne elevation data. Eos 89(10), 93-94. https://doi.org/10.1029/2008eo100001
### Panama: official Atlantic/Pacific watershed boundary
The original KML states that an official Panamanian Atlantic/Pacific watershed boundary replaced a 22.56 km HydroBASINS regional seam. Its exact supplying agency, original file, download route, and version were not recorded. The following MiAmbiente / SINIA government datasets are plausible candidates, **not confirmed matches** to the coordinates in this file:
- Sistema Nacional de Informacion Ambiental (SINIA), `Cuencas Hidrograficas` (listed as an open-data SHP): https://sinia.gob.pa/datos-abiertos-y-geoservicios/
- SINIA SHP linked from that listing: https://sinia.gob.pa/datos/Cuencas_Hidrograficas_250k_Po.zip
- MiAmbiente, `Cuenca Hidrografica 250000`, government ArcGIS feature service: https://geoportal.miambiente.gob.pa/server/rest/services/Hosted/Cuenca_Hidrogr%C3%A1fica_250000/FeatureServer/0
- Corresponding service metadata: https://geoportal.miambiente.gob.pa/server/rest/services/Hosted/Cuenca_Hidrogr%C3%A1fica_250000/FeatureServer/info/iteminfo
No exact geometric correspondence to these particular Panamanian layers has been established. Their publication on government portals does not, on its own, establish a specific permission to redistribute this derived KML under an open-data license.
## Existing geometry
The supplied KML is one LineString with 53,198 vertices. Its pre-existing description reports remaining micro-alignments of 0.276 km (North America to Panama), 0.195 km (Panama Canal polygon-topology closure), and 0.063 km (Panama to South America). The Southern HydroBASINS Level-3 limit is described as near 52.76 degrees south. These notes come from the original file and have not been independently validated.
## Copyright, attribution, and redistribution status
HydroSHEDS version 1 data are copyrighted by World Wildlife Fund, Inc. (2006-2022), and include other third-party contributions. WWF has not verified the altered divide in this repository and does not warrant its accuracy or fitness. The complete required attribution/disclaimer is specified in **Exhibit B** of the HydroSHEDS v1 technical documentation linked above and should be consulted in full for any distribution.
HydroBASINS v1 is governed by the specific HydroSHEDS v1 license, which includes redistribution restrictions. The original Panamanian dataset and its applicable license have not been conclusively identified. **No MIT, CC0, CC BY 4.0, ODbL, or other blanket open license is asserted for the KML in this repository.** These attribution notes do not grant additional rights or establish that current redistribution is authorized.
HydroSHEDS v2 has separately published products under CC BY 4.0, but **this KML has not been reconstructed from v2**, and that newer license does not automatically apply to coordinates derived from v1.
## Outstanding provenance work
Identify and verify the original Panamanian source geometrically; document its permissions; identify the precise HydroBASINS v1 inputs; and establish permission for continued standalone KML distribution or regenerate the divide from sources that expressly permit it.
