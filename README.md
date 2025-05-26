Jupyter notebook updated 09/06/2024

Jupyter notebook updated 09/20/2024  
Changes:  
Preview temperature dependent Nyquist labelling issue addressed  
Simplified linear regression weighting function by eliminating constants and values that cancel  
Fixed issue that made error bars on arrhenius plot too small  

Jupyter notebook updated 11/22/2024
Changes:
Added an extract_number function to extract the EISPOT_#.DTA # and sort .DTA files in order before assigning them a replicate number within each target temperature.

Jupyter notebook updated 12/10/2024
Changes:
Changed file date and time retrieval from OS last time modified to .DTA internal timestamp, which is written at the first data point collected. This adjusts all times in files forward the duration of the EIS run.

# Major Update 5/26/2025--> The Beneficence of Austin
## Changes:
- Updated 4 compatibility with new Quincy
- Improved temperature determination
- Added pre-fitting dataset exclusion
- Improved Nyquist previews
- Improved truncation functionality
- Outlier testing and exclusion added
- Improved commenting
- Refactored all code and defined functions where appropriate
