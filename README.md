### Introduction
This repository contains the code for Car Detection and Color Classification.

---

### Repository Structure

```
├── color_classification.py
├── color_recognition_api
│   ├── color_histogram_feature_extraction.py
│   ├── __init__.py
│   ├── knn_classifier.py
├── Haarcascades
│   └── haarcascade_car.xml
├── README.md
├── requirements.txt
├── sample_videos
│   ├── car_driving.mp4
│   └── car.png
├── test.data
├── training.data
└── training_dataset
    ├── black
    ├── blue
    ├── green
    ├── orange
    ├── red
    ├── violet
    ├── white
    └── yellow
```

---

### Requirements and Implementation
- All the requirements can be installed by running the command `pip3 install -r requirements.txt`

- You can add a video of your choice in [sample_videos](https://github.com/shrenik-jain/car-color-detection/tree/main/sample_videos) or use the [default video](https://www.youtube.com/watch?v=e_WBuBqS9h8)

- Running the command `python3 color_classification.py` would execute the code

---

### References

- [color_recognition_api](https://github.com/ahmetozlu/color_recognition/tree/master/src/color_recognition_api) -> For Real-Time color Detection
