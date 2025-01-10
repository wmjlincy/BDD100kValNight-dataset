# BDD100kValNight+
We analyzed the nighttime image labels in BDD100k's validation set and found that low light conditions lead to frequent label omissions and errors, impacting model precision. 

Mislabeling, such as confusing "Truck" with "Car" or misidentifying signs, is common. 

The "Sign" category is often missed or mislabeled due to unclear text, and bounding box placement for "Light" is inconsistent, especially for distant lights. 

Many target boxes in the nighttime dataset are hard to annotate manually or with models, particularly in complex scenes with pedestrians and vehicles, as shown in Figure below. 

These issues pose significant challenges for both annotation and detection.


![image](https://github.com/user-attachments/assets/533a2005-24ec-4e39-aaf1-a2b303b33c44)

The left image showcases manually annotated bounding boxes, while the middle image displays the inference results from our model (embedding AutoSelector into the YOLOv7 object detection model). 
The image on the right illustrates the visualization of applying the LEDNet model for low-light enhancement. When using the low-light enhanced image (right) as a reference, it becomes apparent that the manual annotations have numerous omissions (left, with red ellipses highlighting the missed bounding boxes and categories). In contrast, our model demonstrates the capability to accurately annotate them.
