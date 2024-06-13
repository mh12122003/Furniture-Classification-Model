# Furniture Classification Tool
This is the Group Machine Learning Project for COSC2753 Machine Learning course - Semester 2024A by Team SG_T2_G3

## Project Requirement
For the Furniture dataset, there are 06 categories: beds - 6578 images; chairs - 22053 images; dressers - 7871 images; lamps - 32402 images; sofas - 4080 images; tables - 17100 images, with a total of 90084 images. For every category, there are 17 interior styles: (a) Asian; (b) Beach; (c) Contemp; (d) Craftsman; (e) Eclectic; (f) Farmhouse; (g) Industrial; (h) Media; (i) Midcentury; (j) Modern; (k) Rustic; (l) Scandinavian; (m) Southwestern; (n) Traditional; (o) Transitional; (p) Tropical and (q) Victorian  
There are three tasks in this project:  
Task 1: Classify images according to furniture category (beds; chairs; dressers; lamps; sofas; tables)  
Task 2: Recommend 10 furniture items in our dataset which is similar to the input furniture item image from users. You are required to define a metric of “similarity” between two furniture items.  
Task 3: The extension of the model in Task 2, the recommended furniture items must be in the same interior styles with the style of the input images. In order to fulfill this task, you are required to build a model to recognize the style of a furniture item.  

## Instructions to run the models
Please execute the notebooks in this order:  

- Place Furniture_Data.zip in this folder.  

- General: Export_to_CSV -> Resampling_Technique -> EDA  

- Task 1: self_built_model1 / self_built_model2 -> Task 1   

- Task 2: VGG_model / ResNet50_model -> Task 2  

- Task 3: AlexNet_model -> Task 3  

