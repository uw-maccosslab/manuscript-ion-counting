# Manuscript for ion counting
[![DOI](https://zenodo.org/badge/649092539.svg)](https://doi.org/10.1021/acs.jproteome.5c00593?urlappend=%3Fref%3DPDF&jav=VoR&rel=cite-as)

This github repo most of the input files and the analyses used in the manuscript. Any files not located here are freely and openly accessible on the [PanoramaWeb](https://panoramaweb.org/MacCoss_ModifiedOrbitrapAstralZoom.url). MS data files can also be found on ProteomeXchange under the unique identifier [PXD064536](https://proteomecentral.proteomexchange.org/cgi/GetDataset?ID=PXD064536).

## Description of scripts

* HeLa_IsoWindow_Figs2-5_FigS1-2_S6-7_TableS1-2.Rmd: This file contains the processing for Figures 2-5, S1-2, S6-7, and Tables S1-2.
  - Figure 2: Acquisition rate and cycle time comparisons between the Orbitrap Astral and prototype Orbitrap Astral Zoom mass spectrometers
  - Figure 3: Detections of precursors and protein numbers between the Orbitrap Astral and prototype Orbitrap Astral Zoom MS
  - Figure 4: Coefficient of variance (CV) comparison between the Orbitrap Astral and prototype Orbitrap Astral Zoom MS
  - Figure 5: Ion counting for ions per peptide  
  - Figure S1: Injection time analysis comparing different isolation windows and input HeLa material 
  - Figure S2: Lower abundance proteins and precursors are gained at higher amounts of HeLa material
    
* EV_MMCC_Fig6_FigS8.Rmd: This files contains the processing for Figures 6 and S8.
  - Figure 6: Extracellular vesicle (EV) matrix-matched calibration comparing the Orbitrap Astral and prototype Orbitrap Astral Zoom MS
  - Figure S8: Detections of protein and precursors, CV, and other ion statistics
    
* Ion_Calibration_Table1_FigS3-5.Rmd: This file contains the code for calibrating the number of ions between different instruments
  - Table 1: Comparison of calibration to ions/sec for various ThermoFisher Scientific MS instruments and analyzers
  - Figure S3: Fragmentation pattern of various compounds used for calibration
  - Figure S4: Plots of Glu[1]-Fibrinopeptide B signal intensity of various fragment ions and number of ions for calibration
  - Figure S5: Comparison of calibration between the Orbitrap Astral and prototype Orbitrap Astral Zoom with various compounds

Any questions regarding the ion calibration code or manuscript, please feel free to contact (maccoss@uw.edu). 

We are currently working on a GUI or Skyline external tool for quick and easy use for calibration. 
