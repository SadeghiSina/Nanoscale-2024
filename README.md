# Nanoscale-2024:
## Here is the custom-implemented Closed-Loop Autonomous Code; the autonomous code contains the real-time data processing part within the second cell.
## The developed Bayesian optimization framework was utilized in the the following papers:
### paper 1 (published in Nanoscale):
#### https://pubs.rsc.org/en/content/articlehtml/2024/nr/d3nr05034c
### paper 2 (published in Advanced Energy Materials):
#### https://advanced.onlinelibrary.wiley.com/doi/full/10.1002/aenm.202302303
## While running the code, it asks for the directory path containing the .csv files; raw absorption and PL spectra as well as the light reference, wavelengths and dark references associated with the absorption and PL spectroscopy, and FR.
## User only needs to copy and paste the directory path in the box provided by the code and press enter.
### FR is the file that includes experimental conditions; each row represents one condition as follows:
### column 1: reaction temperature
### column 2: CuI volumetric flowrate
### column 3: OA-CuI volumetric flowrate
### column 4: OAm-CuI volumetric flowrate
### column 5: ODE-CuI volumetric flowrate
### column 6: CsOleate volumetric flowrate
### column 7: OA-CsOleate volumetric flowrate
### column 8: ODE-CsOleate volumetric flowrate
### column 9: PFO volumetric flowrate
### column 10: number of residence times to wait to initiate the in-situ characterization 
### column 11: always zero meaning no washing is required
