# BDD100kValNight-dataset
We analyzed the nighttime image labels in BDD100k's validation set and found that low light conditions lead to frequent label omissions and errors, impacting model precision. 
Mislabeling, such as confusing "Truck" with "Car" or misidentifying signs, is common. 
The "Sign" category is often missed or mislabeled due to unclear text, and bounding box placement for "Light" is inconsistent, especially for distant lights. 
Many target boxes in the nighttime dataset are hard to annotate manually or with models, particularly in complex scenes with pedestrians and vehicles, as shown in Figure 9. 
These issues pose significant challenges for both annotation and detection.
