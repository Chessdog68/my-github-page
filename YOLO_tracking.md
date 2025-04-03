---
layout: default
---

## Object Detection During the Denman Voyage (RSV Nuyina) - Progression
This was a bit of fun I had conducting some object detection on Antarctic creatures. 
The idea was to capture creatures of the wild as we passed them, identify them, then log the captures to a file. 
It did not work out this way due to CCTV zoom capability and no control being a non-invasive coding project.
So the project rendered the results as seen below, still fun. 
You can just make out myself on the heli deck!

The for this project to run on any web based CCTV, find the url link via the Google Dev tools.

#To use this repository
# To use this repository
1. Run `CCTV_Camera_Listen.py` to retrieve the camera frames and save them to your desired directory.
2. Run `YOLO_Detection_from_CCTV.py` from your desired directory. Considering I am just using a pre-trained model for this fun, the below is all that was required. YOLO certainly does make it easy!

```js
# Load a pretrained YOLO11n model
model = YOLO("yolo11n.pt")
  # Run inference on the source
        results = model(source)  # list of Results objects

```
3. Finally, run `Video_from_YOLO_Detection.py`, which outputs the MP4 as seen below.
<img src="https://raw.githubusercontent.com/hughsLab/my-github-page/main/assets/film/ship_fun.gif" alt="Ship Fun GIF" width="640" height="480" />


_All sky pi5_

[back](./)