# CropEffCal: DEA Efficiency Calculator Shiny App

**CropEffCal** is a Shiny app that helps analyze agricultural efficiency using Data Envelopment Analysis (DEA). Users can upload Excel files and perform efficiency calculations at farmer, tehsil, or zone levels, and compare results across crops and states.
**Features**
Single State DEA analysis (Farmer/Tehsil/Zone level)
State-wise crop comparison
Crop-wise comparison within a state
Interactive bar plots (Plotly)
Downloadable DEA results (CSV)

---

## How to Run the App (Quick Start)

### 1. Install Required Packages in R

Open R or RStudio and run:

install.packages(c(
  "shiny", "readxl", "dplyr", "Benchmarking", 
  "DT", "bslib", "shinybusy", "ggplot2", "plotly"
))

### 2. Download ZIP

Click the green Code button → Download ZIP

Unzip the folder on your computer and copy the file path

In R or RStudio:

setwd("path/to/unzipped/CropEffCal")
shiny::runApp()

### 3. Example dataset
The zip contains the plot level summary data of 2020-21 for all the crops and states to be used as an example dataset. User may select any plot level summary data for the analysis. Do not change anything in the dataset downloaded from the Department of Economics and Statistics website and upload it.
