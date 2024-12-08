# **Exploring Patterns of Environmental Justice in LA due to HOLC Redlining**

## **About**
This project investigates the legacy of historical redlining practices on environmental justice (EJ) outcomes and biodiversity observations in Los Angeles. By integrating data on environmental indicators, socioeconomic factors, historical HOLC maps, and recent biodiversity observations, we aim to understand how past injustices continue to shape present-day environmental and ecological realities.

## **Repository Structure**

- `analysis_files/`                # Folder containing analysis-related files
- `.DS_Store`                      # macOS system file (generally ignored by Git)
- `.gitignore`                     # Git ignore file to exclude unnecessary files
- `EJ impacts of Redlining.Rproj`   # R project file for analysis
- `LICENSE`                        # License file for the project
- `README.md`                      # Project documentation
- `analysis.html`                  # Generated HTML report
- `analysis.qmd`                   # Quarto markdown file for analysis

## **Data Overview**

### **Environmental Justice (EJScreen)** 
- **File**: `ejscreen/EJSCREEN_2023_BG_StatePct_with_AS_CNMI_GU_VI.gdb`  
- **Source**: [EPA Site](https://www.epa.gov/ejscreen/download-ejscreen-data)

### **HOLC Redlining Data**
- **File**: `mapping-inequality/mapping-inequality-los-angeles.json`  
- **Source**: [Mapping Inequality project, Digital Scholarship Lab, University of Richmond](https://dsl.richmond.edu/panorama/redlining/#loc=5/39.1/-94.58)

### **Biodiversity Observations**
- **File**: `gbif-birds-LA.shp`  
- **Source**: [Global Biodiversity Information Facility (GBIF)](https://www.gbif.org)

## **Author**
Sanjay Poudel
