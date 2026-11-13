---
# MIOP terms
methodology_category: sample collection
project: NOAA NWFSC Cook Inlet Beluga Whale
purpose: biodiversity assessment objective [OBI:0001969]
analyses: filtration [OBI:0302885], environmental material collection process [OBI:0600012]
geographic_location: Cook Inlet [GAZ:00051076], Turnagain Arm [GAZ:00051080], Kenai River [GAZ:00197390]
broad_scale_environmental_context: marine biome [ENVO:00000447], marine photic zone [ENVO:00000209], freshwater biome [ENVO:00000873]
local_environmental_context: oceanic epipelagic zone biome [ENVO:01000035], marine benthic biome [ENVO:01000024], freshwater river [ENVO:01000297], estuary [ENVO:00000045]
environmental_medium: sea water [ENVO:00002149], fresh water [ENVO:00002011]
target: deoxyribonucleic acid (DNA) [NCIT:C449], environmental DNA [NCIT:C169106]
creator: Zachary Gold
materials_required: filtration [OBI:0302885]
skills_required: sterile technique, pipetting skills, standard molecular technique, research vessel experience
time_required: 180
personnel_required: 1
language: en
issued: 2026-11-10
audience: scientists
publisher: NOAA Pacific Marine Environmental Laboratory Ocean Molecular Ecology Program; University of Washington Cooperative Institute for Climate, Ocean, & Ecosystem Studies
hasVersion: 1.0.0
license: CC0 1.0 Universal
maturity level: mature

# FAIRe terms
samp_category: sample
env_broad_scale: marine biome [ENVO:00000447], marine photic zone [ENVO:00000209], freshwater biome [ENVO:00000873]
env_local_scale: oceanic epipelagic zone biome [ENVO:01000035], marine benthic biome [ENVO:01000024], freshwater lake biome [ENVO:01000252], estuary [ENVO:00000045]
env_medium: sea water [ENVO:00002149], fresh water [ENVO:00002011]
habitat_natural_artificial_0_1: 0
samp_collect_method: Nasco Swing Sampler, hand deploy
samp_collect_device: Nalgene bottle
samp_size: 1000
samp_size_unit: mL
---

# NOAA NWFSC eDNA Collection Protocol for MCE eDNA Filters using a Vacuum Pump

## PROTOCOL INFORMATION

### Minimum Information about an Omics Protocol (MIOP)

- MIOP terms are listed in the YAML frontmatter of this page.
- See [MIOP_definition.md](https://github.com/BeBOP-OBON/0_protocol_collection_template/blob/main/MIOP_definition.md) for list and definitions.

### Making eDNA FAIR (FAIRe)

- FAIRe terms are listed in the YAML frontmatter of this page.
- See <https://fair-edna.github.io/download.html> for the FAIRe checklist and more information.
- See <https://fair-edna.github.io/guidelines.html#missing-values> for guidelines on missing values that can be used for missing FAIRe or MIOP terms.

### Authors

- All authors known to have contributed to the preparation of this protocol, including those who filled in the template.
- Visit https://orcid.org/ to register for an ORCID.
- Date is the date the author first worked on the protocol.

| PREPARED BY  | AFFILIATION  | ORCID        | DATE       |
| ------------ | ------------ | ------------ | ---------- |
| Kim Parsons | NOAA NWFSC  | 0000-0003-4580-3651 |2026-11-10|
|Zachary Gold	|Ocean Molecular Ecology, NOAA PMEL|	0000-0003-0490-7630	|2026-11-10|

### Related Protocols

- This section contains protocols that should be known to users of this protocol.
- Include the link to each protocol.
- Include the version number and release date (if available).
- Internal/External: "Internal" are derivative or altered protocols, or other protocols in this workflow. "External" are protocols from manufacturers or other groups.

| PROTOCOL NAME | LINK         | VERSION      | RELEASE DATE | INTERNAL/EXTERNAL |
| ------------- | ------------ | ------------ | ------------ | ----------------- |
| NOAA-PMEL-OME_eDNA_DiscFilters_Extraction_Protocol_Centrifuge | https://github.com/HanWeinrich/NOAA-PMEL-OME_eDNA_DiscFilters_Extraction_Protocol_Centrifuge_BeBOP/blob/main/NOAA-PMEL-OME_eDNA_DiscFilters_Extraction_Protocol_Centrifuge.md  | 1.1.1  |	2025-11-14 |Internal |

### Protocol Revision Record

- Version numbers start at 1.0.0 when the protocol is first completed and will increase when changes that impact the outcome of the procedure are made (patches: 1.0.1; minor changes: 1.1.0; major changes: 2.0.0).
- Release date is the date when a given protocol version was finalised.
- Description of revisions includes a brief description of what was changed relative to the previous version.

| VERSION | RELEASE DATE | DESCRIPTION OF REVISIONS |
| ------------- | ------------- | ------------- |
| 1.0.0 | 2026-11-10 | Initial release |

### Acronyms and Abbreviations

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
|CICOES| Cooperative Institute for Climate, Ocean, & Ecosystem Studies
| CTD | Conductivity Temperature Depth |
|DNA	|Deoxyribonucleic acid|
|eDNA	|environmental DNA|
|EtOH| Ethanol|
|MCE|Mixed Cellulose Ester|
|NOAA|National Oceanic and Atmospheric Administration
|NWFSC	|Northwest Fisheries Science Center|
|OME	|Ocean Molecular Ecology|
|PMEL	|Pacific Marine Environmental Laboratory|
|PPE| Personal protective equipment |
|qPCR|Quantitative Polymerase Chain Reaction|
|RO| Reverse Osmosis|
|ROV| Remotely Operated Vehicle|
|UW| University of Washington|

### Glossary

| SPECIALISED TERM | DEFINITION |
| ------------- | ------------- |
| Field blank | Sampling negative control. Typically, distilled or reverse osmosis water is run through a filter like an eDNA water sample to control for contamination in the field sampling step.  |
|Kemmerer sampler |Specialized water sampling device designed to collect discrete water sample grab from specific vertical depths.|

## BACKGROUND

### Summary

Water collection and filtration protocol using 1 µm MCE 47 mm disk filters to collect environmental DNA from marine, freshwater, and estuarine ecosystems. This collection and filtration protocol was used by NWFSC for the Characterizing the Prey Landscape of Endangered Cook Inlet Beluga Whales Using an eDNA Time Series project.

### Method Description and Rationale

This protocol describes the collection and filtration of water samples through a 1 µm sterile disc MCE filter using vacuum filtration to capture eDNA and DNA-containing particulates. The DNA captured on the filter will later be extracted from these samples for multi-locus metabarcoding and qPCR analysis. The protocol is intended for water collected with a nalgene bottle mounted on Nasco Swing Sampler or Kemmerer sampler, but it can also be employed for samples collected by hand.

### Spatial Coverage and Environment(s) of Relevance

This protocol has been used to filter eDNA from hundreds of samples taken from Cook Inlet, Turnagain Arm, and Kenai River.

### Personnel Required

One person with pipetting experience. Recommend research vessel experience, but not required.

### Safety

This protocol uses bleach and ethanol, both of which are classified as hazardous chemicals. Appropriate PPE must be worn, and standard safety procedures should be followed to avoid skin and eye exposure.

### Training Requirements

Molecular biology training (including, at a minimum, sterile technique and pipetting technique) is required to conduct this protocol. Experience with going to sea and sample collection under seagoing conditions is encouraged; at a minimum, personnel should be trained in the filtering protocol in a laboratory/docked ship setting beforehand.

### Time Required to Execute the Procedure

The time needed varies widely based on the number and type of samples collected. For a majority of our sampling water samples are collected from shore using the Nasco swing sampler. Triplicate samples are collected from each sampling time point from the surface. Collecting water samples takes between 10-30 minutes, depending on access and weather conditions (e.g. snow+ice). We've also collected samples using a Kemmerer sampler deployed from a bridge or dock.

The vacuum filtration set-up for three singular samples from the silt laden Cook Inlet takes on average 45 minutes. Pending the turbidity of the water, the filtering of a single sample take upwards of 1 hour. 

The total collection and filtering time for a singular collection event with trplicate 1 L samples is 180 minutes (3 hours) on average. More casts, more samples = more time.

## EQUIPMENT

- Description: E.g., "filter".
- Product Name and Model: Provide the official name of the product.
- Manufacturer: Provide the name of the manufacturer of the product.
- Quantity: Provide quantities necessary for one application of the standard operating procedure (e.g., number of filters).
- Remark: For example, some of the consumables may need to be sterilized, some commercial solutions may need to be diluted or shielded from light during the operating procedure.

For a singular cast with three unique samples taken (one sample per Niskin):

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| **Durable equipment** |
| Vacuum pump | Millipore Chemical Duty Pump | Proactive Environmental Products | 1 | Can be substituted with generic|
| Vacuum tubing | Nalgene 3/8" tubing | Cole Palmer | 3 | Need to be cut into 1-2 ft pieces with a razor blade. Can be substituted with generic tubing of the same diameter. |
| Vacuum filter manifold | PVC, 3 branch, Vacuum Filtration Manifold |Made in USA| 3 | Can be subsituted with generic, must be sterilizable. |
|Rubber stopper|Rubber stopper for filtration manifolds |Generic|3| Must fit on the filter manifold and fit the filter holder|
| Nalgene bottles | 1 L Nalgene wide-mouth lab quality amber HDPE bottles | Thermo Scientific | 3 | Can be substituted with generic - must be opaque, well-sealing, and sterilizable. |
| Carboy | 20 L Nalgene rectangular carboy with lid equipped with tube couplings | Generic | 1 | Must fit with tubing to vacuum manifold and vacuum pump |
| Forceps |  Plastic Tweezers Acid Resistant, ESD Safe ID 51-1625-0224 | Oxford Instruments | 1 per sample | Can be substituted with generic. |
| Cooler |  Generic cooler, ideally 70 L| Generic | 1 per sample | Can be substituted with generic. Ideally large enough to hold all samples and ice packs and can maintain cold temperatures well. |
| Blue ice |  Technical ice | Can be substituted with generic. |
|Wash bottles|Safety wash bottles 500 mL for EtOH, bleach, and RO water|VWR|3|Can be substituted with generic, but recommend purchasing different colored bottles for each reagent. Must be sterilized before use. |
| Bucket | 5-gallon bucket | Generic | 1 |  Optional if there is a sink or other catchment for wastewater.|
| Tabletop covering | Disposable plastic or paper table covering| Generic | 1 |  |
| Bungee cords | Bungee cords | Generic | 10 | Varying sizes recommended, eye bolts and cord can be used alternately.  |
|Pre-filter adapter|eDNA Pre-filter adapter| Smith-Root|3|Optional, only needed when filtering directly from a Niskin or inline.|
| **Consumable equipment** |
| Foil | Aluminium Foil | Generic | 1 | |
|Stericup filter holder| Millipore Stericup filter holder |Generic|3| Must fit on adapter to rubber stopper. Can not be substituted for this protocol.|
|Stericup adapter|Stericup plastic adapter for manifold|Generic|3| Must fit in the rubber stopper|
|1 µm 47 mm Nitocellulose Mixed ester (MCE) filter|Sterlitech 1 µm MCE filter|Generic|3| Can not be substituted for this protocol.|
| Label tape | VWR general-purpose laboratory labeling tape | VWR |1  | Can be substituted with generic. |
| Parafilm | Parafilm  | Sigma Aldrich |60 cm | |
| Kimwipes | Delicate task wipes | Kimtech |2 wipes| Can be substituted with generic. Must be lint-free.|
| Nitrile gloves | Powder free nitrile gloves | Fisher Scientific |2 pairs | Can be subsituted with generic nitrile gloves. Does not come sterile; must be sterilized before use (10% bleach followed by 70% EtOH). |
| Field notebook | Durable, hardcover lab notebook | Generic | 1 | Dedicated to fieldwork. | 
| Writing utensils | Pens and sharpies | Generic | 2 |Not made of wood - must be able to be wiped down with bleach/EtOH.  |
| **Chemicals** |
| 70% EtOH | Molecular biology grade ethanol | 10 mL |  |
| 10% bleach | Hypochlorite bleach | Clorox | 400 mL| Remake every ~5 days as bleach decomposes quickly at 10% concentration. The majority is used in bottle/tube sterilization.|
| Distilled water | Distilled water | Generic | 400 mL| Ideally would use Ultrapure 18 MΩ RO water for field blanks and cleaning, however in rural Alaska distilled water from a grocery store is often the only clean water available. |

## STANDARD OPERATING PROCEDURE

### Preparation

**Glove Sterilization:**
When sterilizing any equipment or filtering, sterile nitrile gloves must be used. Gloves directly from the box are not considered sterile. To sterilize, squirt 10% bleach solution from a squirt bottle onto new pair of gloves and rub hands together, then squirt with EtOH to get rid of bleach residue. Nitrile gloves should be worn at all times during the sterilization, sampling, filtering, preservation, and storage steps.

**Prepare Longmire Buffer:**

We recommend making Longmire buffer solution in batches in a sterile molecular laboratory setting.

Reagents:

* 1M Tris-HCl (Trizma Base), pH 8.0
* 0.5M EDTA (Ethylenediaminetetraacetic acid, disodium salt), pH 8.0
* 5M NaCl
* 10% SDS (Sodium Dodecyl Sulfate)
* Molecular Grade Water
* 0.22um PES filter funnel to sterilize reagents

**NOTE** Previous Longmire solutions included Sodium Azide which required mask, gloves, and lab coat, and powdered SDS which required the use of a mask. The sodium azide is not included, and we purchase all reagents pre-made, thus the SDS is already suspended.

1. Connect filter cup to vacuum pump
2. Add water to filter cup, see volume below
3. Add all other reagents, following volume table in the order they are listed

 Reagent | Volume | Final Concentration | 
| ------------- | ------------- | ------------- | 
|1M Tris| 50 mL| 100mM|
|0.5M EDTA| 50 mL| 100mM|
|5M NaCl| 1 mL| 10mM|
|10% SDS| 50 mL| 0.5%|
|Molecular Grade Water| 324 mL| --|

4. Apply vacuum pressure to filter reagents
5. Remove upper portion of filter cup, close lower container with provided lid
6. Lab container with "Longmire Buffer", the date, and your initials.

**Bucket Sterilization:**

1. Create a 10% bleach solution directly in a bucket (4-6 L). Seal the lid carefully and shake for 2-3 minutes.
2. Empty the 10% bleach solution. Fill the carboy with 3-4 L of RO water and shake for 1-2 minutes. Repeat this RO wash step two more times (= 3 rinses in total).
9. Once complete, close the bucket with a lid, label, and close with tape.

**Bottle Sterilization:**

One sterile bottle is required for each sample and each field blank.

Bottle Sterilization Method (RO Available):

1. Create a 10% bleach solution in one of the buckets (6-10 L total, depending on needs).
2. Fill 4-6 bottles at a time with 10% bleach solution; fill to the top and seal with a lid. Allow to sit for 7 minutes, then flip the bottle upside down. Allow to sit for 7 more minutes.
3. Pour 10% bleach from these bottles into the next set of bottles or reuse bleach for further sterilization needs.
4. Each bottle needs to be rinsed with distilled water. Fill each Nalgene bottle with ~200 mL of RO, and then shake for 30-45 seconds. Repeat process 2x (= three rinses in total).
5. Shake out excess distilled water dumped (doesn’t need to be entirely dry), close it with the cap, and then wrap the top with parafilm to maintain sterility. Always wrap in the direction the cap tightens, so clockwise.
   
**Bench Space Preparation:**

* Set up the vacuum pump and carboy on a work station.
* Sterilize the workstation by wiping surfaces with kimwipes and a 10% bleach solution before every sampling event. If the workspace surface is wood, use the tabletop covering to cover the sample processing area.

**Cooler + Technical Ice Preparation:**

* Sterilize cooler as described above for work station.
* Ensure technical ice/blue ice is in freezer.

**Immediately Before Sampling:**
* In the lab, all sterile fittings and Stericups should be left in the packaging until ready to use. Organize your vacuum and clear tubing, carbuoy, and Stericup filters.
* Prepare field sampling kit of cooler with ice packs, Kemmerer and/or Nasco Swing sampler, clipboard/notebook, and bottles for all samples at a station prior to collection. 

**Field Sampling Records:**

When eDNA sampling in the field, there should be a corresponding record sheet or field notebook. Record the date, sample #, site name, lat/long, cast #, depth, and any other associated notes (e.g., filtering issues, sampling device, cast deployment time).

### Sampling
Ensure sterile gloves are used when handling equipment.

This protocol is designed for samples collected with a Kemmerer sampler  - the samples are expected to be discrete and sealed masses of water that can be transferred to a 1 L Nalgene bottle without contamination (typically from the spout/spigot of the Kemmerer bottle). For our samples, Kemmerer bottles are manually triggered to close at a specified depth using a mechanical messenger. 

When using a Nasco Swing Sampler, place the nalgene bottle with the lid off onto the bottle holder. Extend the sampler as far as feasible into the water without stepping into it. 

Fill a 1 L Nalgene bottle with 1 L of sample water.  After collecting, place immediately into cooler out of direct sunlight and heat. Immediately proceed to filtering after transport back to the lab. Make sure to label and store bottles on ice for up to 12 hours (>4 hours is not ideal). Note the length of time a water sample sits in the fridge in the field notebook.

### Filtration

* Back in the lab, set up filter manifold with labeled Stericups outfitted with 1 µm 47 mm MCE filters - one for each sample.
* Pour sample into Stericup
* Turn on vacuum manifold. Do not exceed 8 psi. Adjust vacuum strength as needed.
* Refill Stericup (250 mL) until all 1 L sample is filtered. (**NOTE** High glacial silt content will dramatically increase filtering effort and time needed to process samples.)
* Run vacuum until filter is dry
* Once filtering is complete, carefully remove the Stericup clear plastic portion from the base. **CAREFUL NOT TO SCRAPE AGAINST FILTER**
* Using sterile forceps, transfer to a pre-labeled 1.5 mL corresponding to the sample # that is preloaded with longmire buffer.

### Sample Preservation

Filter should be submerged in 1 mL Longmire solution into 1.5 mL tube or 4 mL into a 5 mL tube with the filter. Longmire buffer is a lysis buffer that can preserve DNA at room temperature.

### Storage

Store preserved samples at room temperature in a dry, cool location. Samples can be shipped with no cold storage, provided that shipping temperatures are not excessively hot or below freezing.

Samples should be extracted as soon as is timely and sterile, but the longmire buffer has been demonstrated to preserve DNA for at least a year, if needed.

### Quality Control

A field blank consisting of sterile RO or distilled water in a 1 L nalgene at the start and end of field sampling. An additional field blank should be filtered every few days of sampling. 

### Basic Troubleshooting Guide

**Issue 1:** Clogged filter.

**Solution:** If a filter clogs prior to filtering 1 L (water no longer passes through), then denote the volume filtered and continue filtering through a new  filter. Repeat until 1 L is filtered. Mark each additional Smith-Root, record additional sample names and notes, and denote volumes filtered for each in the field notebook.

## REFERENCES
- Kim M. Parsons, Meredith Everett, Marilyn Dahlheim, Linda Park; Water, water everywhere: environmental DNA can unlock population structure in elusive marine species. R. Soc. Open Sci. 1 August 2018; 5 (8): 180537. https://doi.org/10.1098/rsos.180537
- Longmire et al. Use of “Lysis Buffer” in DNA Isolation and Its Implication for Museum Collections. 1 May 1997. Museum of Texas Tech University, Occasional Papers, Number 163.



