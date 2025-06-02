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

###2. Clone via git (option 1)
git clone https://github.com/divyacrotu/CropEffCal.git
setwd("CropEffCal")
shiny::runApp()

###OR Download ZIP (Option 2)

Click the green Code button → Download ZIP

Unzip the folder on your computer

In R or RStudio:

setwd("path/to/unzipped/CropEffCal")
shiny::runApp()


