# dlts-aco-marc2mods

## Overview
* This repo contains source metadata, transformed metadata,
  stylesheets, and schema for MARC to MODS transformations.

#### Directory structure:

| directory          | comment                                                      |
|--------------------|--------------------------------------------------------------|
| `xsl/`             | contains various `MARCXML` to `MODS` stylesheets             |
| `xsd/`             | contains various `XML Schema` definitions                    |
| `partner-marcxml/` | `MARCXML` files as received from Partner institution         |
| `marcxml/`         | `MARCXML` after KARMS processing. Used to generate MODS      |
| `dlts-aco-mods/`   | files generated using `dlts_aco_marc_to_mods.xsl` stylesheet |
| `mods-3-5/`        | files generated using `MARC21slim2MODS3-5.xsl` stylesheet    |


#### Mapping information:

To view the source assets on the ACO site, populate the following URL template:

`http://dlib.nyu.edu/aco/book/<digitization id>`

```
digitization id        MARC 003_001
-----------------------------------
columbia_aco000074 --> NNC_3128238  
columbia_aco000076 --> NNC_3073605  
columbia_aco000200 --> NNC_3071251  

```
