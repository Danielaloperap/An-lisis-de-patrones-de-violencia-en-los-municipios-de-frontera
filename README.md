# Armed Violence Patterns Along the Colombia–Venezuela Border (2011–2022)

## Overview

This repository contains the dataset used to study territorial and temporal patterns of armed violence across municipalities located along the Colombia–Venezuela border between 2011 and 2022.

The dataset integrates information on victimization events, armed group presence, illicit economies, armed clashes, and border-related characteristics. The data were compiled from multiple public institutional sources and organized as a municipality-year panel dataset.

## Study Area

The study covers 222 municipalities located in seven Colombian departments within the Colombia–Venezuela border region:

* Arauca
* Boyacá
* Cesar
* Guainía
* La Guajira
* Norte de Santander
* Vichada

## Temporal Coverage

2011–2022

## Unit of Analysis

Municipality-year observations.

**Total observations:** 2,664.

## Repository Structure

```text
data/
    colombia_venezuela_border_violence_panel_2011_2022.csv
    data_dictionary.csv
```

## Dataset Contents

The dataset includes variables related to:

* Victimization events
* Presence of armed groups (AGC, ELN, EPL, FARC, and FARC dissidents)
* Coca cultivation
* Coca eradication
* Destruction of drug-processing laboratories
* Armed clashes
* Border municipality status
* Proximity to the international border (measured as the minimum distance to the nearest border crossing in kilometers)
* Peace agreement period
* Presidential administration period

A detailed description of all variables is available in:

```text
data/data_dictionary.csv
```

## Data Sources

The dataset was compiled using publicly available information from the following sources:

* Registro Único de Víctimas (RUV)
* Centro Nacional de Memoria Histórica (CNMH)
* Defensoría del Pueblo
* Sistema Integrado de Monitoreo de Cultivos Ilícitos (SIMCI)
* Ministerio de Justicia y del Derecho
* Agencia Nacional de Minería (ANM)
* Colombia en Mapas

Additionally, the variable **minimum_distance_to_border_crossing_km** was constructed by the author using geographic information from Colombia en Mapas to estimate the minimum distance between each municipality and the nearest international border crossing with Venezuela.

## Code Availability

The dataset used in this study is publicly available in this repository.

Analysis scripts will be released upon publication of the associated manuscript.

## License

Please refer to the LICENSE file for information regarding the use and distribution of this dataset.

## Contact

For questions regarding the dataset, please use the GitHub repository issue tracker.

