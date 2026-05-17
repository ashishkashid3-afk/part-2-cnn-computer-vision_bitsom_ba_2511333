## Task 6- CNN Concept Explaination
# What is convolution?
Convolution is the process where we exploit spatial structure, detect local patterns from image dataset. In this process we derive important feature such as edges, structure and shapes from images which helps CNN to learn visual pattern. It is core building block of every CNN.
## Why is pooling used?
After convolution extarct features, the feature maps are large and contain redundant information. Pooling is used to reduce the size of feature maps while keeping important information. Pooling also used to reduce computation, reduce model overfitting and provides translation invariance.
## Why is ReLU commonly used in CNNs?
Rectified Linear unit (ReLU) is activation function who introduces non-linearity in to the model and helps the network learn complex image pattern efficiently. It Also speed ups the training effectively with many layers, helps the network focus on the most relevant feature.
## Why are CNNs better than regular feed-forward networks for image data?
CNN are specialised for grid like data while FFN are specialised for tabular or non-spatial data. CNN excel at recognizing spatail hierarchies i.e. shapes and edges in images throgh convolutional  layers. So CNN are better than regular FFN for image data.

## Task 7-Business Use Case mapping
# Real world Domain- Manufacturing
This computer vision solution  can be used in the Automobile Manufacturing industry for surface detect detection. For example aesthetic part like exhust silencer or mudgurd or petrol tank of any Two wheeler.
In this case CNN model can automatically identify defects such as dents, scratches, line marks on manufactured two wheeler assembly using image data from camera installed on production lines.
# This helps manufaturer to :
-Improve product quality 
-Reduce manual inspection report
-Detect defect faster
-Minimize production loss
-Increase Overall Equipment Efficiency
# Dataset Source Link-'C:\\Users\\DELL\\Desktop\\bitsom_ba_2511333_Kashid_Ashish_Assignment5\\BITSoM BA - Module 5 - Dataset\\ai_project_synthetic_datasets\\part_2_cnn_computer_vision'