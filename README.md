# W209-Final-Project-Group3_Section6
This is a git repo for W209 Final Project for Savita, Tymon, Andrew and Blake. <div style="page-break-after: always;">
Our Kaggle project is to predict Forest Cover types by image data: https://www.kaggle.com/c/forest-cover-type-prediction/data

## Background/ Project Descirption 
The study area includes four wilderness areas located in the Roosevelt National Forest of northern Colorado. Each observation is a 30m x 30m patch. You are asked to predict an integer classification for the forest cover type. The seven types are:

- 1 - Spruce/Fir
- 2 - Lodgepole Pine 
- 3 - Ponderosa Pine
- 4 - Cottonwood/Willow 
- 5 - Aspen 
- 6 - Douglas-fir 
- 7 - Krummholz

Data Fields 
- Elevation - Elevation in meters 
- Aspect - Aspect in degrees azimuth 
- Slope - Slope in degrees 
- Horizontal_Distance_To_Hydrology - Horz Dist to nearest surface water features 
- Vertical_Distance_To_Hydrology - Vert Dist to nearest surface water features 
- Horizontal_Distance_To_Roadways - Horz Dist to nearest roadway 
- Hillshade_9am (0 to 255 index) - Hillshade index at 9am, summer solstice 
- Hillshade_Noon (0 to 255 index) - Hillshade index at noon, summer solstice 
- Hillshade_3pm (0 to 255 index) - Hillshade index at 3pm, summer solstice 
- Horizontal_Distance_To_Fire_Points - Horz Dist to nearest wildfire ignition points 
- Wilderness_Area (4 binary columns, 0 = absence or 1 = presence) - Wilderness area designation 
- Soil_Type (40 binary columns, 0 = absence or 1 = presence) - Soil Type designation 
- Cover_Type (7 types, integers 1 to 7) - Forest Cover Type designation 

The wilderness areas are: 

- 1 - Rawah Wilderness Area 
- 2 - Neota Wilderness Area 
- 3 - Comanche Peak Wilderness Area 
- 4 - Cache la Poudre Wilderness Area 

## Questions to Answer
- Can we build a model that predicts what types of trees grow in an area based on the surrounding characteristics?
- What kinds of trees are most common in the Roosevelt National Forest?
- What tree types are confused most ?

## Documentation Explaination 
### Final Project
- EDA Folder
  - DataPreprocessing_FeatureEngineeeringV1_CompareML.ipynb: Data Preprocessing & Feature Engineering
  - W207_Final_Project_MLPv2.ipynb: MLP Model evaluation
- Model Folder
  - W207_Final_Project_KNN.ipynb: KNN Model evaluation
  - W207_Final_Project_MLPv2.ipynb Neural Network Model evaluation
  - FinalNotebook-DataProcssing-FeatureEng-ModelComparison.ipynb: Multiple Model Comparison and Conclusions

### Midterm Project Submission within EDA folder:
- W207_Final_Project_EDA: Our Exploratory Data Analysis
- W207_Final_Project_Metric_of_Evaluation: Our determination of metrics of evaluation
- W207_Final_Project_MLP: Our first neural network model attempt and evaluation, any potential challenges, and next steps
