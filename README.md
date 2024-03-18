# Vehicle Color Recognition

This repository contains a Python implementation for vehicle detection and color classification using the K-Nearest Neighbors (KNN) algorithm and Haar Cascades for object detection.

## Purpose

The primary purpose of this project is to demonstrate the application of computer vision techniques and machine learning algorithms for identifying vehicles in images or videos and classifying their colors. This can be useful in various scenarios, such as traffic monitoring, parking management, or automotive industry applications.

## Repository Structure

```
├── color_classification.py
├── color_recognition_api
│   ├── color_histogram_feature_extraction.py
│   ├── __init__.py
│   ├── knn_classifier.py
├── Haarcascades
│   └── haarcascade_car.xml
├── LICENSE
├── README.md
├── requirements.txt
├── sample_videos
│   ├── car_driving.mp4
│   └── car.png
├── test.data
├── training.data
└── training_dataset
```

## Installation and Usage

1. Clone the repository: https://github.com/shrenik-jain/vehicle-color-recognition.git

2. Install the required dependencies: `pip3 install -r requirements.txt`

3.  You can add a video of your choice in [`sample_videos`](sample_videos) or use the [default video](https://www.youtube.com/watch?v=e_WBuBqS9h8)

4. Run the color classification script: `python3 color_classification.py`

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request. For major changes, it's recommended to discuss them first by opening an issue.

To contribute to this project:
1. Fork the repository
2. Create a new branch for your feature or bug fix
3. Make your changes and commit them with descriptive commit messages
4. Push your changes to your forked repository
5. Submit a pull request to the main repository

Please ensure that your code follows the project's coding style and that you have added relevant tests and documentation.

## License

This project is licensed under the [MIT License](LICENSE).

## References

- [color_recognition_api](https://github.com/ahmetozlu/color_recognition/tree/master/src/color_recognition_api)

## Contact

If you have any questions, suggestions, or feedback, feel free to reach out to me through [email](mailto:shrenikkjain81@gmail.com) or visit my [website](https://shrenik-jain.github.io/).

<br>

Developed by [*Shrenik Jain*](https://shrenik-jain.github.io/)
