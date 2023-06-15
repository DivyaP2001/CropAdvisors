CropAdvisors
A Farming Assistance System By using Recommendation System in Machine Learning.

Problem Definiation:
Design and develop a crop, fertilizer, and pesticide recommendation system to assist farmers in making informed decisions regarding crop selection, appropriate fertilizers, and pesticides based on their specific farming conditions. The system should leverage data analysis and machine learning techniques to provide accurate and personalized recommendations.

Problem Description:
Agricultural productivity heavily relies on the judicious selection of crops, appropriate application of fertilizers, and effective management of pests and diseases. However, farmers often face challenges in determining the most suitable crops to grow, identifying the optimal fertilizers for their soil type, and deciding on the right pesticides to combat pests and diseases. To address these challenges, a recommendation system is needed to provide farmers with personalized advice based on their specific farming conditions, including soil type, climate, crop history, and pest occurrences.

Technology Used:
1] Front End technology: HTML CSS, JavaScript. 2] Machine Learning: Python, Flask (Web developer framework) 3] Backend technology: Flask, mongoDB. 4] Code editor: Visual studio Code, Notepad, Anaconda3, Python IDLE 5] Web Browser: Google Chrome, Mozilla firefox, opera

Methodology
Crop Recommendation
1. Dataset Acquisition
2. Taking input values
3. ML Model Training & creating .pkl file
    i. Using Ensembling Technique with majority voting technique.
       a] Random Forest Machine Learning Technique.

4. Crop Recommendation
   i. Loading .pkl model file to recommend crop based on input data
Fertilizer Recommendation
1. Dataset Acquisition
   i. NPK values for different crops
   ii.Sources:
      a] The Fertilizer Association of India,
      b] Indian Institute of Water Management etc
2. Taking input values
3. Difference b/w desired & actual
   1] High
   2] Low
   3] Upto the mark
4. Dictionary based Suggestions (Solutions from verified sources)
Pesticide Recommendation
1. Data Acquisition
   a] image Scraping from Google Images
   b] Providing pest labels
2. Data Cleaning & Data Augmentation
   i.  Data is cleaned to remove not useful content
   ii. The dataset is augmented so as to increase the variability
3. DL model creation
4. Pest Detection & Pesticide Recommendation
How to Run Project on LocalHost :
Prerequisite: Download the project files from Master branch

Download Python IDLE or Visual Studio Code or any Python distribution like Pycharm
Download Anaconda3 for easy hosting.
Create new environment using command --> conda create -n env_name python==3.7.0 (preferred on Anaconda shell prompt)
Activate environment using command --> conda activate env_name
Install requirements by typing (cd ProjectFolder) --> pip install -r requirements.txt
Now run app.py by writing command --> python app.py
Conclusion
In conclusion, the development of a crop, fertilizer, and pesticide recommendation system based on soil chemistry and atmospheric conditions using random forest and CNN (Convolutional Neural Network) has shown promising results.The random forest algorithm can effectively handle complex relationships between soil chemistry variables, atmospheric conditions, and crop performance. It can identify important features and make accurate predictions based on the input data. The CNN model, on the other hand, can extract meaningful features from spatial data of pesticides imagery data, allowing for a more in-depth understanding of the agricultural landscape. By considering atmospheric conditions in combination with soil chemistry, the CNN can capture the dynamic and spatial aspects of crop growth, enabling precise recommendations.By leveraging both random forest and CNN models, the recommendation system can provide personalized and data-driven suggestions for crop selection, optimal fertilizer composition, and pesticide usage. The system takes into account the unique characteristics of each field, such as soil fertility, nutrient deficiencies, and environmental conditions, to optimize crop yield and minimize the use of fertilizers and pesticides. In conclusion, the crop, fertilizer, and pesticide recommendation system based on soil chemistry, atmospheric conditions, and the integration of random forest and CNN models holds great promise in optimizing agricultural practices, improving crop yield, and promoting sustainable farming methods. Continued research and development in this area can further enhance the accuracy and usability of such systems, benefiting both farmers and the environment.
