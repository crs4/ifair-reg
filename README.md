This repository contains the semantic metadata model for a registry of biomedical research compliant with FAIR principles.
The registry contains metadata of clinical trials. It is based on the [FDP](https://github.com/FAIRDataTeam/FAIRDataPoint-Spec) from which it inherits the hierarchical structure and the set of generic metadata. 

The `studies` of the registry are `dcat:Dataset`. The FDP model, based on DCAT is extended to include some attributes specific of the biomedical domain. The new attributes are modelled through [SIO](https://github.com/MaastrichtU-IDS/semanticscience) properties
