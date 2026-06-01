<div align="center">

# Airborne Object Detection Dataset

<p>
  <img width="100%" src="images/banner.jpg" alt="Airborne Object Detection Dataset Banner">
</p>

A large-scale RGB dataset for airborne object detection and air surveillance research.

</div>

---

# Overview

The Airborne Object Detection Dataset is a large-scale RGB image dataset developed to support research in airborne object detection, classification, and surveillance systems. The dataset contains manually annotated airborne objects collected from diverse real-world environments and is intended for training and evaluating modern deep-learning-based object detectors.

The dataset includes five airborne object categories:

* Airplane
* Helicopter
* Drone
* Parachute
* Bird

The images exhibit substantial variations in object size, orientation, lighting conditions, backgrounds, weather conditions, and camera viewpoints, making the dataset suitable for real-world surveillance applications.

---

# Dataset Statistics

| Property           | Value            |
| ------------------ | ---------------- |
| Total Images       | 80,179           |
| Number of Classes  | 5                |
| Annotation Type    | Bounding Boxes   |
| Annotation Format  | YOLO             |
| Image Modality     | RGB              |
| Application Domain | Air Surveillance |

---

# Classes

| Class ID | Class Name |
| -------- | ---------- |
| 0        | Airplane   |
| 3        | Helicopter |
| 2        | Drone      |
| 4        | Parachute  |
| 1        | Bird       |

---

# Example Image of Dataset's images

<img src="images/examples/airplane.jpg" width="600">

---

# Annotation Format

All annotations are provided in YOLO format:

```text
<class_id> <x_center> <y_center> <width> <height>
```

Example:

```text
0 0.5234 0.4812 0.1521 0.2105
```

Coordinates are normalized with respect to image dimensions.

---

# Dataset Structure

```text
Airborne_Object_Dataset/
│
├── train/
│   ├── images/
│   └── labels/
│
├── val/
│   ├── images/
│   └── labels/
│
├── test/
│   ├── images/
│   └── labels/
│
└── dataset.yaml
```

---

# Applications

This dataset can be used for:

* Airborne object detection
* Air surveillance systems
* UAV and drone detection
* Small object detection
* Real-time object detection
* Multi-object tracking
* Deep learning research

---

# Challenges

The dataset contains several challenges commonly encountered in practical surveillance systems:

* Small object detection
* Scale variation
* Motion blur
* Complex backgrounds
* Illumination changes
* Similar visual appearance between classes
* Long-range airborne targets

---

# Citation

If you use this dataset in your research, please cite:

```bibtex
@dataset{YourDataset2025,
  author = {Your Name},
  title = {Airborne Object Detection Dataset},
  year = {2025},
  publisher = {Zenodo},
  doi = {DOI_HERE}
}
```

---

# License

This dataset is released for research and educational purposes. Please cite the dataset when used in academic publications.

---

# Contact

For questions regarding the dataset, please contact:

Name Freshta Alizada

Email Freshta.alizada579@gmail.com
