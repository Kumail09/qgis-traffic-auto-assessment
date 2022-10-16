Structure
===================

Project Structure
^^^^^

Project 1 : Macro Location
*****

:maps#situation-macro:

Range: `25 km`

Background:	`Open Streetmap`

Layer 1: `admin_bounday`
`Source <https://data.gov.be/nl/dataset/b47f2ffd-ebc9-413c-903f-d83af520fcdb>`_

Rename legend `admin_Boundery` to `Gemeentegrenzen`


``Note: in this version, we will only do Vlaanderen. There are 2 more regions for a later project, with similar build-up but different sources.``

Project 2 : Meso Location
****

:maps#situation-meso:

Range: `5 km`

Background:	`Open Streetmap`

Project 3 : Meso Location
****

:maps#id-1:


Range: `5 km`

Background:	none

Layer 1: `luchtfoto Vlaanderen winter 2021 (orthomozaik)`

`Source layer 1 <https://www.geopunt.be/download?container=omwrgb21vl&title=Orthofotomozaiek,%20middenschalig,%20winteropnamen,%20kleur,%202021,%20Vlaanderen>`_	`upload to server of mozaiks`


Project 4 : Micro Location
****
Range: `100 m`

Background:	`Open Streetmap`



Project 5 : Micro Location
****

Range: `50m`

Background:	`GRBgis`

Source Files Uploaded to Server


Project 6 :	Micro location
***
Range: `75m`

Resample to 100m

Background:	none

Layer 1: `luchtfoto Vlaanderen winter 2021 (orthomozaik)`
`Source layer 1	upload to server of mozaiks`


Project 6 : Bus network macro
****

Range: `10 km`

Background:	`OSM or alternative basemap`

Layer 1:	`Reiswegen De Lijn`
`Source layer 1 <https://geoservices.informatievlaanderen.be/overdrachtdiensten/Reiswegen/wfs?service=WFS&request=getcapabilities>`_

Layer 2:	`tec_lines`
`Source layer 2	<https://geodata.tec-wl.be/arcgis/services/Lignes/MapServer/WMSServer?request=GetCapabilities&service=WMS>`_

layer 3:	`Réseau de bus de la STIB - harmonisé selon`
`Source layer 3	<http://geoservices-inspire.irisnet.be/geoserver/stib_mivb/wms?service=WMS&version=1.3.0&request=GetCapabilities>`_

layer 3 alternative:	`stib_lines`
`Source layer 3 alternative	<http://10.1.10.177:8080/geoserver/bm_public_transport/wfs?service=wfs&version=1.1.0&request=GetFeature&typeName=bm_public_transport:stib_lines&outputFormat=shape-zip&srsName=EPSG:31370>`_

Project 7 : Bus network micro
****
Zoom to 1km

Range:	`750m`

Background:	`Open streetmap or alternative`

Layer 1:	`Reiswegen De Lijn`
`Source layer 1	<https://geoservices.informatievlaanderen.be/overdrachtdiensten/Reiswegen/wfs?service=WFS&request=getcapabilities>`_

Layer 2:	`Haltes De Lijn`
`Source layer 2	<https://geoservices.informatievlaanderen.be/overdrachtdiensten/Haltes/wfs?service=WFS&request=getcapabilities>`_

Layer 3:	`tec_lines`
`Source layer 3	<https://geodata.tec-wl.be/arcgis/services/Lignes/MapServer/WMSServer?request=GetCapabilities&service=WMS>`_

Layer 4:	`tec_stops`
`Source layer 4	<https://geodata.tec-wl.be/arcgis/services/Poteaux/MapServer/WMSServer?request=GetCapabilities&service=WMS>`_

Layer 5:	`Réseau de bus de la STIB - harmonisé selon`
`Source layer 5	<http://geoservices-inspire.irisnet.be/geoserver/stib_mivb/wms?service=WMS&version=1.3.0&request=GetCapabilities>`_

Layer 6	`Réseau de bus de la STIB - harmonisé selon`
`Source layer 6	<http://geoservices-inspire.irisnet.be/geoserver/stib_mivb/wms?service=WMS&version=1.3.0&request=GetCapabilities>`_

Layer 5 and 6 alternative part 1	`stib_lines`
`Source layer 5 and 6 alternative part 1 <http://10.1.10.177:8080/geoserver/bm_public_transport/wfs?service=wfs&version=1.1.0&request=GetFeature&typeName=bm_public_transport:stib_lines&outputFormat=shape-zip&srsName=EPSG:31370>`_

Layer  5 and 6 alternative part 2	`stib_stops`
`Source layer 5 and 6 alternative part 2	<http://10.1.10.177:8080/geoserver/bm_public_transport/wfs?service=wfs&version=1.1.0&request=GetFeature&typeName=bm_public_transport:stib_stops&outputFormat=shape-zip&srsName=EPSG:31370>`_


Project 8: `Bike network functional`
****
``Legend: show only those that are on the map + show BFF first + no titles + change 'rer_velo' to 'Brusselse intergewestelijke fietsroutes'``

Range:	`10 km`

Background:	`open street map or alternative`

Layer 2: `rer_velo`
`Source layer 2	<http://10.1.10.177:8080/geoserver/bm_bike/wfs?service=wfs&version=1.1.0&request=GetFeature&typeName=bm_bike:rer_velo&outputFormat=shape-zip&srsName=EPSG:31370>`_

layer 3: `icr`

`file on server	Is to be labeled as FRN, ICR=french`
`Source layer 3:	<http://10.1.10.177:8080/geoserver/bm_bike/wfs?service=wfs&version=1.1.0&request=GetFeature&typeName=bm_bike:icr&outputFormat=shape-zip&srsName=EPSG:31370>`_

Layer 4: `fietssnelwegen`

`Source layer 4	<https://geoservices.vlaamsbrabant.be/FSW/MapServer/WFSServer?>`_

Layer 5: `bff file on server`

Source layer 5:	`https://metadata.vlaanderen.be/srv/dut/catalog.search#/metadata/cdf0ec2d-69d2-49cd-8f35-596be010745e`

Project 9 : Bike network recreational
****
Legend: change to the same names but without underscore and capitalize 'Promenade Vert Bike'

Range:	`10 km`

Background:	`open streetmap or alternative`

Layer 1:	`fietsnetwerk lange afstand`

`Source layer1 	<http://trip.toerismevlaanderen.be/arcgis/rest/services/>`_

Layer 2:	`promenade_vert_bike`

`Source layer 2:	<http://10.1.10.177:8080/geoserver/bm_bike/wfs?service=wfs&version=1.1.0&request=GetFeature&typeName=bm_bike:promenade_vert_bike&outputFormat=shape-zip&srsName=EPSG:31370>`_

Layer 3: `fiets_knooppunten_trajecten`

Layer 4: `fiets_knooppunten_routes` || "nodes"

`Source layer 3 and 4:	<https://geoservices.vlaamsbrabant.be/FSW/MapServer/WFSServer?>`_


Project 10	Pedestrian network
****
legend: change name to the same but without underscore

Range:	3 km

Background:	Open streetmap

Layer 1:	wandel_trajecten

Source layer 1:	https://metadata.vlaanderen.be/srv/dut/catalog.search#/metadata/621a818c-273b-4d33-86fa-0fc9d549b786

Layer 2:	wandel_knooppunten

Source layer 2:	https://metadata.vlaanderen.be/srv/dut/catalog.search#/metadata/621a818c-273b-4d33-86fa-0fc9d549b786

Layer 3:	trottoirs

Source Layer 3:	GRB file upload, tag voetpad				I have requested help, there is an issue with identifying the right layer --> this cannot be fixed, so no layer 3 for this project

Project 11	Horse network
****
legend: change name to the same but without underscore

Range:	3 km

Background:	Open streetmap

Layer 1:	ruiter_trajecten

Source layer 1:	https://metadata.vlaanderen.be/srv/dut/catalog.search#/metadata/0addb054-f131-4790-a437-c094b0324707

Layer 2:	ruiter_knooppunten

Source layer 2:	https://metadata.vlaanderen.be/srv/dut/catalog.search#/metadata/621a818c-273b-4d33-86fa-0fc9d549b786

Project 12	Train network
****
this map is missing?

Range:	10 km

Background:	standard map or alternative

Layer 1:	sncb_nmbs_lines

Source layer 1	https://data.gov.be/nl/dataset/69ff70d1-012a-4483-9a75-03233f145556					at the bottom of the page, there are 3 options: gml, wms, xml

Layer 2:	sncb_nmbs_stops

Source layer 2	https://bruxellesdata.opendatasoft.com/api/v2/catalog/datasets/nmbs-stations/exports/shp

Layer 3	overwegen

Source layer 3	https://opendata.infrabel.be/api/v2/catalog/datasets/geoow/exports/shp

Project 13
****
Road hierarchy			This needs to be in 1.0, but has to be drawn because the information is only partially available digitally.
Range:						I will make a final attempt to get this map by tomorrow
Background:						https://www.vlaanderen.be/basisbereikbaarheid/toekomstgerichte-vervoersnetwerken/wegennetwerk
Layer 1:	Vlaanderen: new map					doc 4
Layer 2:	Bxl
layer 3	Wallonia

Project 14
****
Atlas der buurtwegen			This will be a 1.1 version item
Range:	75m
Background	airial standard
Layer 1:	Atlas der buurtwegen

Layer 2: 	Wijzigingen atlas der buurtwegen
