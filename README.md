# MY472-AT24-final

[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/9NdxGEaf)

The instructions are available in the file [MY472-AT24-final-instructions.md](/MY472-AT24-final-instructions.md).

## Primary Contact Information

-   **Name**: Anonymous Student
-   **Email address**: [a.student\@lse.ac.uk](mailto:a.student@lse.ac.uk){.email}
-   **Phone**: +44 1234 567890
-   **Time Zone**: GMT

## Brief Description & Prerequisites

**Project title:** Democracy in the Hands of Children: The Impact of Biases in Generative AI on Children’s Understanding of Democratic Participation

**Prerequisites:** The HuggingFace Inference API is used to generate the data for this project. Therefore, a free HuggingFace account, as well as an access token for the API, are required. In addition, a MongoDB database is created, so MongoDB needs to be installed and activated. Please find instructions for these installations in the `.Rmd` file of this repository.

## Data Download Link

The data generated and used in this project can be downloaded through the dropbox page [here](https://www.dropbox.com/scl/fo/i7dvz8cv3ln0ee74zzane/APwyVBOuEvOP950lky0Am0A?rlkey=9nysqfziz5nw9vvcc4t0052nu&st=xod7qnul&dl=0), or directly onto your computer with [this link](https://www.dropbox.com/scl/fo/i7dvz8cv3ln0ee74zzane/APwyVBOuEvOP950lky0Am0A?rlkey=9nysqfziz5nw9vvcc4t0052nu&st=xod7qnul&dl=1). OR the code in the `.Rmd` file directly enables you to download it to a defined working directory. In case there are any issues with the Dropbox link, a backup link has been created with Google drive, such that the data can be downloaded [here](https://drive.google.com/drive/folders/1Rol9c29KDCPiTcPZCGHYGmzwmGWw_qFK?usp=sharing).

## Folder Structure

```{bash}

my472-at24-final-50280/
├── 00_helper_data/
│   ├── CNTR_RG_2024_3035.*       # Shapefile components for EU country boundaries. 
│   ├── eu_youth_dem_data.csv     # CSV file with youth cleaned democracy data from EU survey. 
│   ├── eu_youth_democracy_2024.xlsx # Downloaded excel file with EU youth democracy data. 
├── 01_main_text_data/
│   ├── age_6/                    # Text data for children aged 6.
│   │   ├── Austria.txt           # One text file with respective answers
│   │   ├── ...                   # for each country in the EU. 
│   │   └── Sweden.txt            
│   ├── age_9/                    # Text data for children aged 9.
│   │   ├── Austria.txt           # Description for Austria
│   │   └── ...                   # and all other EU countries respectively. 
│   ├── age_14/                   # Text data for children aged 14.
│       ├── Austria.txt           
│       └── ...                   
├── 02_secondary_image_data/
│   ├── age_6/                    # Images for children aged 6.
│   │   ├── Austria.jpeg          # One image visualising the most poorly understood
│   │   ├── ...                   # concept relating to democratic participation for each 
│   │   └── Sweden.txt            # respective country in the EU. 
│   ├── age_9/                    # Images for children aged 9.
│   │   ├── Austria.jpeg          
│   │   └── ...                    
│   ├── age_14/                   # Images for children aged 14.
│       ├── Austria.jpeg          
│       └── ...                   
├── 03_visualisations/
│   ├── eu_youth_partic_map.pdf   # Map visualisation of youth participation across the EU. 
│   ├── political_participation_austria_poland.pdf # Visualisation of generated images. 
├── README.md                     
├── MY472-AT24-final-report.Rmd   # RMarkdown report for the project.
├── MY472-AT24-final-report.html  # Html version of the report. 
├── MY472-AT24-instructions.md    

```
