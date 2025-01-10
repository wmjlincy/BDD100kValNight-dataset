![f8fd74881f00f321107a7433ff1bae9](https://github.com/user-attachments/assets/66e6e28f-bf7a-4ee3-89d4-e03718b6207a)# BDD100kValNight-dataset
We analyzed the nighttime image labels in BDD100k's validation set and found that low light conditions lead to frequent label omissions and errors, impacting model precision. 
Mislabeling, such as confusing "Truck" with "Car" or misidentifying signs, is common. 
The "Sign" category is often missed or mislabeled due to unclear text, and bounding box placement for "Light" is inconsistent, especially for distant lights. 
Many target boxes in the nighttime dataset are hard to annotate manually or with models, particularly in complex scenes with pedestrians and vehicles, as shown in Figure 9. 
These issues pose significant challenges for both annotation and detection.

![image](https://github.com/user-attachments/assets/9afda039-8120-4e52-bea8-27df7bf9186c)
