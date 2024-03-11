# ImpactObjects

ImpactObjects are JSON Object representing an environmental impact.
They must obey to the following structure :
- Level 1: Three-letter code for Life Cycle Step
- Level 2: 3 to 5 letters code for Impact or Flux indicators

## Life Cycle Steps
The accepted Life Cycle Step are optional and are the following :
- BLD: Build/Manufacturing
- DIS: Distribution
- USE: Usage
- EOL: End Of Life

## Indicators (Impact Categories and Fluxes)
The accepted Impact/Flux indicators are optional and are the following :
- AP - Acidification -	mol H+ eq
- GWP - Climate change -	kg CO2 eq
- CTUe - Ecotoxicity, freshwater -	CTUe
- Epf - Eutrophication, freshwater -	kg P eq
- Epm - Eutrophication, marine - kg N eq
- Ept - Eutrophication, terrestrial -	kg N eq
- CTUh-c - Human toxicity, cancer -	CTUh
- CTUh-nc - Human toxicity, non-cancer -	CTUh
- IR - Ionising radiation,human health - kg U235 eq
- LU - Land use -	Dimensionless
- MIPS - Material Input per Unit of Service -	kg
- ODP - Ozone depletion -	kg CFC-11 eq
- PM - Particulate matter -	Disease occurrences
- POCP - Photochemical ozone formation -	kg NMVOC eq
- ADPf - Resource use, fossils -	MJ
- ADPe - Resource use, minerals and metals -	kg Sb eq
- TPE - Total Primary Energy -	MJ
- WU - Water use -	m3 eq

WARNING : For PCR compliance, the required indicators must be provided. 
