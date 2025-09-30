**Proposal** for a 2024 <a href="https://envirostewards.rutgers.edu/" target="_BLANK">Rutgers Environmental Stewards</a> (RES) project emphasizing the utility of **GIS for stewardship projects** managed by <a href="https://www.fopos.org/" target="_BLANK">Friends of Princeton Open Space</a> (FOPOS). Project overview page and details: [https://pmgreen.github.io/res/](https://pmgreen.github.io/res/)

<img width="30%" alt="RUESNJAES_H_RED_BLACK_RGB" src="https://github.com/user-attachments/assets/fd7dd65b-5296-46b3-b8fc-6b394e815be6" />

<img align="right" width="15%" alt="FOPOS bw horiz" src="https://github.com/user-attachments/assets/73803622-95fd-4489-9390-b3b57e1227d1" />
<br /><br />
<hr />

✅ = done

🟧 = future step

🔷 = adaptation (changes to original project proposal)


<hr />

# GIS for Friends of Princeton Open Space Riparian Restoration Project

## Overall goal

The primary purpose of the project is to facilitate the collection and
presentation of data for the NJDEP funded [Riparian Restoration Project](https://www.fopos.org/riparian-restoration-project),
with the stated aim to "rehabilitate riparian areas that protect lake
and stream banks from erosion, slow and store stormwater, and filter
pollutants from runoff."

<img width="50%" alt="priinceton_hydro_small" src="https://github.com/user-attachments/assets/729e89a1-c624-44be-a2f1-0aa5dc16a4e1" />
  
*Princeton Hyrdo's map of the overall project area*

<hr />

**Note:** *QGIS* is a free and open source geographic information system (GIS). 
*QField* is a free and open source mobile app for data
collection that is integrated with QGIS.<br />
<img width="3.5%" alt="QGIS_logo_minimal svg" src="https://github.com/user-attachments/assets/d0976776-f2d0-497c-801b-ccbcfd0437a4" />
<img width="10%" alt="qfield_for_qgis" src="https://github.com/user-attachments/assets/f114f3f1-f00f-47c7-8048-71d7a496c452" />

<hr />

## Objective 1: Assist with Botanical Surveys

Assist with baseline plant and tree surveys in the area of Mountain
Lakes known as Riparian East

**Measurement:** Data on plants and trees for the project area is
collected in the field and the protocol is documented in Google Docs

**Timeline:** 6-13-24 until 8-31-24

**Tasks**

1. ✅ Review existing plant data protocol with the Stewardship Director

2. ✅ Assist with refining and mapping permanent transects within the project area

3. ✅ Assist with data collection in the field for the forestry inventory in July/August 2024

4. 🟧 Document the protocol in Google Drive in a way that can be easily adopted by future interns, community volunteers and/or school groups of various ages

<hr />

## Objective 2: Facilitate Botanical Data Analysis

**Measurement:** There is a pilot QField project for future data
collection with resulting data shared in Google Drive for evaluation

**Timeline:** 9-1-24 to ~~9-15-24~~ 9-30-24

**Tasks**

1. ✅ Create a map of the study area in QGIS (for printing as well as for use in QField)

2. ✅ Explore the creation of forms in QField for entering complex data using mobile devices

3. ✅ Manually enter the data collected thus far (on paper) into the QField form to test and refine its functionality; this will be iterative, getting feedback from the Stewardship Director and interns

4. ✅ Explore processes for efficiently getting data from QGIS into Google Drive (the flow: QField \> QGIS \> Google Sheets)

<hr />

## Objective 3: Present Data & Document Processes

This objective has two parts: 1. external: publishing summary data from
the baseline surveys and 2. internal: ensuring that the process is clear
and repeatable

**Measurement:** At least one map and project summary have been
publicized and internal Google docs outline how the process may be
replicated next season

**Timeline:** ~~9-15-24~~ 9-30-24 to 10-31-24

**Tasks**

1. ✅ With the Stewardship Director, identify and perform calculations to summarize and reveal patterns in data

2. ✅ Prepare one or more maps for publication (e.g. plant species distribution, tree species distribution) 

3. 🟧 Publish a project summary on the FOPOS site (and/or newsletter or social media), including tie-ins to the general effects of climate change and carbon storage data for the area of
   interest 🔷 adaptation: published here on GitHub
   
   | Project Summaries May Include |
	 | ---------- |
   | percent cover (plant abundance) |
   | status (native, invasive, introduced) |
   | weather |
   | highlights |
   | conservation concern |
   | conservation optimism |
   | species richness per species (no abundance) |
   | total hours |

4. 🟧 With the Stewardship Director, document ideas for continuity of the project with interns, students. or volunteers in a shared Google Doc

5. ✅ Ensure that all project documents and files have appropriate permissions (they are not locked down), that they are backed up, and that they are organized in a way that ensures the ongoing success of the project. calculate invasive native and conservation status

<hr />

## How Climate Change is Included (for the [Forest Inventory](https://github.com/pmgreen/forest_inventory))

We aim to include carbon bank tracking based on the tree inventory, along with a general description of the effects of climate change

#### Formulae (applied in Google Sheets) 
From [Randye Rutberg](https://www.linkedin.com/in/randye-rutberg-350689122) (personal communication to Anna Corichi August 3, 2023)

* `bm Exp dbh = + ( ln )`

From
<a href="https://www.researchgate.net/publication/216811948_National_Scale_Biomass_Estimators_for_United_States_Tree_Species">Jenkins, Jennifer & Chojnacky, David & Heath, Linda & Birdsey, Richard. (2003). National Scale Biomass Estimators for United States Tree Species. Forest Science. 49. 12-35. 10.1093/forestscience/49.1.12.</a>

* Total biomass: `bm=Exp(b0+b1*lndbh)`
* Total biomass of CO (kg): `mass(kg)=bm(kg)*0.5`
* Total carbon absorbed: `total mass *3.67`

### iTree

🔷 adaptation: used <a href="https://www.itreetools.org/tools/i-tree-eco" target="_BLANK">iTree Eco</a> to generate carbon benefiits

<img width="15%" alt="i-Tree_Powered_by_large_tall" src="https://github.com/user-attachments/assets/809cbeb5-9f01-4862-a16f-21a9c997b64d" />
