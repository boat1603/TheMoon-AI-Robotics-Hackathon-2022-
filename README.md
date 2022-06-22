# TheMoon-AI-Robotics-Hackathon-2022
The Moon Team
1. Pattareeya Piravechsakul (pattareeya.prvsk@gmail.com) Responsible for M2
2. Peerawat Rojratchadakorn (peerawat.roj@gmail.com) Responsible for M1
3. Teepakorn Tosawadi (teepakorn.tosa@gmail.com) Responsible for M3

If our code is not reproducible, please contact us via email.

# Dataset preparation
Place dataset into folder "./datasets/Varuna Hackathon 2022"

## Data Exploration
Data Exploration is "00" code file we just explore features from given datasets

## Data preprocessing for M1 and M2
1. Following "01-DataPreprocessing for Data Preparation.ipynb"
2. Following "01-DataPreprocessing for Model Training.ipynb"

# Method 3 (U-Net)
We extend our work futrher using U-Net and scope down the experiment to 4 revisit interval.
From given crop shapefile, we rasterize into GeoTiff format.
The code was provided in 
    "00-Rasterize shapefile using OSGeo for U-Net.ipynb"

The data were random picked from ground truth mask instead of polygon based selection(M1+M2).
You can find the data exploration,training data preprocessing and model training in
1. "00-Features analysis for U-Net.ipynb"
2. "01-DataPreprocessing for U-Net.ipynb"
3. "02-M3-Classification_U-Net.ipynb"
    