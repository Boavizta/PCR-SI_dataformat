# ImpactObjects

ImpactObjects are JSON Object representing an environmental impact.
They must obey to the following structure :
- Level 1: Three-letter code for Life Cycle Step
- Level 2: 3 to 5 letters code for Impact or Flux indicators

The accepted Life Cycle Step are :
- BLD: Build/Manufacturing
- DIS: Distribution
- USE: Usage
- EOL: End Of Life

The accepted Impact/Flux indicators are :
- Acidification (AP) -	mol H+ eq
- Climate change (GWP) -	kg CO2 eq
- Ecotoxicity, freshwater (CTUe) -	CTUe
- Eutrophication, freshwater (Epf) -	kg P eq
- Eutrophication, marine (Epm) - kg N eq
- Eutrophication, terrestrial (Ept) -	kg N eq
- Human toxicity, cancer (CTUh-c) -	CTUh
- Human toxicity, non-cancer (CTUh-nc) -	CTUh
- Ionising radiation,human health (IR) - kg U235 eq
- Land use (LU) -	Dimensionless
- Material Input per Unit of Service (MIPS) -	kg
- Ozone depletion (ODP) -	kg CFC-11 eq
- Particulate matter (PM) -	Disease occurrences
- Photochemical ozone formation (POCP) -	kg NMVOC eq
- Resource use, fossils (ADPf) -	MJ
- Resource use, minerals and metals (ADPe) -	kg Sb eq
- Total Primary Energy (TPE) -	MJ
- Water use (WU) -	m3 eq
