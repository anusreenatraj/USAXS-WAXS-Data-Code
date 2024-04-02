# Nonclassical Crystallization Processes of Single-Crystalline Two-Dimensional Covalent Organic Frameworks (2D COFs): USAXS-WAXS-Data-Code
This repository contains raw data files for in situ USAXS and WAXS experiments, fits obtained from USAXS modeling and code written using Python3 to process USAXS and WAXS data.

# Description of the data and file structure
 
Raw USAXS data are located in the following folders:
	
    /in situ USAXS/Polycrystalline TAPB-DMPDA/Raw Data
    /in situ USAXS/Single-Crystalline TAPB-DMPDA/Raw Data

Results from modeling USAXS data are located in the following folders:
	
    /in situ USAXS/Polycrystalline TAPB-DMPDA/Modeling
    /in situ USAXS/Single-Crystalline TAPB-DMPDA/Modeling

Raw WAXS data are located in the following folders:

    /in situ WAXS/Single-Crystalline TAPB-DMPDA - Standard Conditions/Raw Data
    /in situ WAXS/Single-Crystalline TAPB-DMPDA - High Temp/Raw Data
    /in situ WAXS/Single-Crystalline TAPB-DMPDA - Low TAPB Conc/Raw Data
    /in situ WAXS/Polycrystalline TAPB-DMPDA/Raw Data
		
Pre-reaction mixture (background) WAXS data are located in the following folders:

    /in situ WAXS/Single-Crystalline TAPB-DMPDA - Standard Conditions/Pre Rxn Mix
    /in situ WAXS/Single-Crystalline TAPB-DMPDA - High Temp/Pre Rxn Mix
    /in situ WAXS/Single-Crystalline TAPB-DMPDA - Low TAPB Conc/Pre Rxn Mix
    /in situ WAXS/Polycrystalline TAPB-DMPDA/Pre Rxn Mix
		
Background-subtracted WAXS data will be saved in the following folders upon running the code in "EasyPlot-XRD-DomainSize.ipynb":

    /in situ WAXS/Single-Crystalline TAPB-DMPDA - Standard Conditions/Background-Subtracted Data
    /in situ WAXS/Single-Crystalline TAPB-DMPDA - High Temp/Background-Subtracted Data
    /in situ WAXS/Single-Crystalline TAPB-DMPDA - Low TAPB Conc/Background-Subtracted Data
    /in situ WAXS/Polycrystalline TAPB-DMPDA/Background-Subtracted Data
 
Use the Jupyter Notebook "EasyPlot-XRD-DomainSize.ipynb to plot WAXS data, domain size and normalized FWHM for any given data folder within "in situ WAXS."

Use the Jupyter Notebook "USAXS-plots.ipynb to plot USAXS data for any given data folder within "in situ USAXS."

Use the Jupyter Notebook "USAXS-extract-values-from-model.ipynb to extract required values from fitting of USAXS data within "in situ USAXS."
  

# Sharing/Access information

  Link to publicly accessible ESRF Data Portal (available as open access after 5th February, 2026):

  https://doi.org/10.15151/ESRF-ES-1108937734
  

# USAXS data were collected at:

ESRF, The European Synchrotron Radiation Facility (beam time awarded at ID02 for proposal CH-6646 from 28 Apr to 2 May, 2023)

# WAXS data were collected at:

APS, The Advanced Photon Source (beam times awarded at DND-CAT for multiple proposals during 2021, 2022 and 2023)


