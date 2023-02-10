# thesis_nkohler_ccwbe

# Institution: Geographical Institute of the University of Bern
# Author: Nadine Kohler
# Master thesis

# Title: "Die Entwicklung des Waldes im Kanton Bern basierend auf der klimabedingten Verschiebung der Vegetationshöhenstufen
# Eine partizipative Modellierung von Berner Waldstandorttypen für die Periode 2070 – 2099

# Two python scripts and one ArcMap toolbox model were used to model forest site types for the Canton Bern. This was done twice: once for the concentration pathway RCP4.5 and once for RCP8.5. The vegetation belt scenarios were derived from Zischg et al.(2021, https://doi.org/10.1111/avsc.12621)

# STEP 1: 
# "ccwbe_standorthinweiskarteV2_rcp45" / "ccwbe_standorthinweiskarteV2_rcp85": modells forest site types in the Canton Bern for the altitutinal vegetation belts under the concentration pathway RCP4.5 and RCP8.5, respectively, in a raster data frame. 

# STEP 2: 
# use model "postprocessing2_rcp45" / "postprocessing2_rcp85" in ArcMap toolbox to transform raster outputs into shapefiles

# STEP 3: 
# "ccwbe_standorthinweiskarteV2_rcp45_join" / "ccwbe_standorthinweiskarteV2_rcp85_join": reads shapefiles and joins parameters for each forst site type, adds region (Berner Jura, Berner Mittelland, Berner Oberland) and area ([m2]) per polygon.

# to view modelled forest site types for the Canton of Bern for 2070 - 2099 based on two climate scenarios RCP4.5 and RCP8.5, download data from ZENODO:  https://doi.org/10.5281/zenodo.7586912

