# RIGIS-broadband-availability

Broadband Rhode Island (BBRI), as a participant in the National Telecommunications and Information Administration (NTIA) State Broadband Initiative, has partnered with broadband Internet providers to compile an approximation of where such services are available in the State.

BBRI assembles and submits these data on a semi-annual basis to the NTIA, which are subsequently made available by the NTIA via the National Broadband Map in a collection of online maps, tabular data, and Esri file geodatabases. BBRI has contributed a series of pre-compiled datasets to RIGIS that users should find are more readily accessible and easier to use by a wide variety of GIS software. The data available for download from this web page consist of flat shapefiles (each census block maintains a one-to-one relationship to individual provider records, rather than a one-to-many relationship), are reprojected to the Rhode Island State Plane coordinate system, and include all inland Rhode Island census blocks (not just those less than two square miles).

An attribute field (titled "TOTAL_PROV") that tallies the total number of providers per census block has been added to each shapefile that represents individual wireline technology types. Wireline and wireless technology summary files are also provided that tally the number of technology types and providers per census block, presence/absence of a provider per census block, and the number of providers that offer a given broadband technology type per census block.

## Datasets
* [Summary](./BBRI_wirelineSum12) ([Map](./BBRI_wirelineSum12.geojson))
* [Cable Modem - DOCSIS 3.0](./BBRI_cableDOCSIS12) ([Map](./BBRI_cableDOCSIS12.geojson))
* [Cable Modem - Other](./BBRI_cableOther12) ([Map](./BBRI_cableOther12.geojson))
* [xDSL - Asymmetric](./BBRI_DSLasym12) ([Map](./BBRI_DSLasym12.geojson))
* [xDSL - Symmetric](./BBRI_DSLsym12) ([Map](./BBRI_DSLsym12.geojson))
* [Optical Carrier/Fiber to the End User](./BBRI_fiber12) ([Map](./BBRI_fiber12.geojson))
* [Other Copper Wireline](./BBRI_otherCopper12) ([Map](./BBRI_otherCopper12.geojson))
