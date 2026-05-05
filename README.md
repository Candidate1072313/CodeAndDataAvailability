# Code And Data Availability
Code and data for the MBiol thesis 'The Pitfalls of Global Biodiversity Monitoring: Making Room for Community-Led Initiatives'

## Code
The file **CodeCandidate1072313.qmd** contains the RStudio code used to generate all results.


## Data
The file **ResultsStandardisedMetadataFramework.xlsx** contains the standardised metadata framework required to synthesise camera trap metadata between CoMapeo, Timelapse and GBIF. This is relevant to Section 3.3, and 4.2.

The file **totalSpeciesGrid.csv** contains the downloaded data from QGIS with all biodiversity data across the 10km*10km Mae Suai grid. This is relevant to Section 3.2.

The file **cellsGcomGInv.csv** contains the full set of calculations for G<sub>com</sub> (Completeness Score) and  G<sub>inv</sub> (Ignorance Score), calculated for all 26 10km*10km grid cells across Mae Suai. This is relevant for Section 3.2.

The file **taxonomyGcomGInv.csv** contains the full set of calculations for G<sub>com</sub> (Completeness Score) and  G<sub>inv</sub> (Ignorance Score), calculated for all 14 classes in the 26 10km*10km grid cells across Mae Suai. This contains the classes: Agaricomycetes, Amphibia, Arachnida, Aves, Diplopoda, Gastropoda, Insecta, Liliopsida, Magnoliopsida, Mammalia, Pinopsida, Polypodiopsida, Squamata, Testudines. This is relevant for Section 3.2.

The files **GCom.csv** and **GInv.csv** contain G<sub>com</sub> and G<sub>inv</sub> respectively for the 6 classes with an occurrence record greater than 10 in this region. This includes: Arachnida, Aves, Insecta, Liliopsida, Magnoliopsida and Squamata. Classes with an occurrence record lower than this are too unstable to have their  G<sub>com</sub> and G<sub>inv</sub> successfully analysed in a Principal Component Analysis. This is relevant for Section 3.2.

The files **GComFactors.csv** and **GInvFactors.csv** contain the tables used for the correlation test, with 6 columns containing the classes studied (Arachnida, Aves, Insecta, Liliopsida, Magnoliopsida, Squamata) and 3 columns containing environmental factors (Road Density, Waterway Density and Protected Area Density). Rows correspond to the 26 grid cells. **GComFactors.csv** contains the Completeness Scores, and **GInvFactors.csv** contains the Ignorance Score. This is relevant for Section 3.2.
 
The files **rdaGCom.csv** and **rdaGInv.csv** contain the grouped G<sub>com</sub> and G<sub>inv</sub> for the Redundancy Analysis in Section 3.2. Data were grouped based on the Principal Component Analysis into the broad groups Verbrates (containing Aves and Squamata), Invertebrates (containing Arachnida and Insecta) and Plantae (containing Liliopsida and Magnoliopsida).
