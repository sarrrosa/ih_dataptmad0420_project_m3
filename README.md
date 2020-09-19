# Prediction diamond's price
![Image](https://user-images.githubusercontent.com/63467553/93368573-74dd0200-f84e-11ea-85f2-34e28a98e3b6.png)


## Motivation :blush:
*This is my third project within the Ironhack Analytics Bootcamp (Part time version) in Madrid. The objective of the competition is to predict the diamond's price for a specific given dataset. More information about the competition can be found here: (https://www.kaggle.com/c/dataptmad0420/overview)*

## Overview :gem:
The objective of this project is to predict the the price of **diamonds** depending on their 4Cs and if there are any specific variables to be taken into account that affect diamond price more than others. It is important to have the knowledge background as following in order to understand the basics of this database:

- **Carat:** It refers to the diamond's weight, not size. The price of a diamond does not increase linearly with the increase of the catat. Carat weight is not related to a better diamond, the cut is. 
- **Cut:** A diamond's cut is crucial to the stone's final beauty and value. It takes into account the design and craftsmanship of the diamond, including its weight relative to its diameter. The most important factor of all the 4Cs.
    - Premium
    - Ideal
    - Very good
    - Good
    - Fair
- **Color:** The color of a diamond is scaled within the GIA color grading system. It defines the colour of the diamond. The most colorless is D and it goes to Z. 
    - D: Colorless
    - E: Colorless
    - F: Colorless
    - G: Near colorless
    - H: Near colorless
    - I: Near colorless
- **Clarity:** Is the assessment of small imperfections on the surface and within the stone. Diamond shape and size affects clarity. 
    - IF: Internally flawless (100% free of inclusions - less than 1% of all diamonds are FL clarity)
    - VVS1, VVS2: Very very slightly included (diamonds have minuscule inclusions that are difficult even for a trained eyes to see under 10x magnification)
    - VS1, VS2: Very slightly included (minor inclusions ranging from difficult (v1) to somewhat easy (v2) to see at 10x magnification)
    - SI2: Slightly included (Inclusions are noticeable at 10x magnification. SI diamonds are often best value)
    - I1: Included (clarity have obvious inclusions that are likely to be visible and impact beauty)
- **Depth:** It is important because the depth of the diamond will affect how much light is reflected back to the observer. *A diamond with an ideal depth will reflect most of the light that comes into the diamond.* The ideal depth would be between 59% and 62,3%
- **Table:** A diamond's table is the flat facet on its surface - As the largest facet on a diamond, the table plays a major role in determining how brilliant (sparkly) the diamond is. A bigger table isn't necessary better. The ideal table would be between 53% and 68%
- **Price:** The total price of the diamond
- **X:** Lenght of the diamond
- **Y:** Width of the diamond
- **Z:** Height of the diamond

---

## Data sources :scroll:
 - Database with diamond train
 - Database with diamond test
 - Output data [modelo_pepino.csv] formatted as a `.csv` file.

## Requirements :arrow_forward:

You will need to install and import or have already installed and imported the following Python libraries in order to be able to analyse the data:
- Data analysis:
    - Pandas
    - Sklearn models
    - Numpy
- Data visualisation:
    - Matplotlib
    
## Folder structure :open_file_folder:
```
└── project   
    └── data
        ├── diamonds_train.csv
        ├── diamonds_predict.csv
    ├── notebook
        ├── machine_learning_model_diamond.ipynb
    ├── .gitignore
    ├── README.md
    ├── requirements.txt
```

## How to use :electric_plug:
Download the databases provided and commit cells for local deployment. 

## Machine learning models tested :tada:
    - Decission Tree Regressor
    - Gradient Boosting Regressor
    - LGBM Regressor

## Output :pushpin:
`.csv` file called modelo_pepino.csv to be uploaded to the Kaggle competition.  
