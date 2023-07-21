# Hackathon-Plant-seeds-detection-by-Super-AI-Engineer-Season-3
 Thie repo is a part of Hackathon-Plant-seeds-detection-by-Super-AI-Engineer-Season-3. This competition is detect and count plant seed. After I look around a dataset. I think this problem may be a classification problem more than detection, so I actually select a dectection seed first. After that, the images that cropped from dectection feed to classify seed and count them.
 <br>
<br>
![Hackathon-Plant-seeds-detection-by-Super-AI-Engineer-Season-3](Plat_seed_detect_cover.png)
<br>
<br>

My logic process<br>
Explore data --> Roboflow tool make yolo format dataset --> Yolov8 to detect seed --> Save image detect --> Feed cropped image to eva02 (image classification model) --> Counting --> submit
