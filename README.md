# Animal Detection with YOLOv3

This repository demonstrates how to use YOLOv3 for detecting animals in images. The model identifies specific animal classes from the COCO dataset and highlights them with bounding boxes.

## Features
- Detects animals such as dogs, cats, birds, and more.
- Uses YOLOv3 pre-trained on the COCO dataset for object detection.
- Visualizes detection results using OpenCV and Matplotlib.

---

## Repository Structure
```
.
├── AnimalDetection.ipynb      # Main code in Jupyter Notebook format
├── yolov3.cfg                 # YOLOv3 configuration file
├── yolov3.weights             # Pre-trained YOLOv3 weights
├── coco (1).names             # COCO dataset class names
└──sample_images/             # Folder for input images (add your own images here)

```

---

## Requirements
Install the required libraries using `pip`:
```bash
pip install numpy opencv-python matplotlib
```

---

## Setup Instructions
1. Clone this repository:
   ```bash
   git clone https://github.com/moulikaboga/animal-detection-yolov3.git
   cd animal-detection-yolov3
   ```

2. Add the necessary files to the repository:
   - `yolov3.cfg`: YOLOv3 configuration file.
   - `yolov3.weights`: Pre-trained weights file. [Can be downloaded from clicking this link ](https://github.com/patrick013/Object-Detection---Yolov3/raw/refs/heads/master/model/yolov3.weights)
 
   - `coco (1).names`: COCO dataset class names.

3. Add input images to the `sample_images/` directory for testing.

---

## Usage
1. Open the Jupyter Notebook `AnimalDetection.ipynb`.
2. Update the file paths in the code to match your setup.
3. Run the notebook to detect animals in the input image(s).
4. The output image with bounding boxes will be displayed using Matplotlib.

---

## Supported Animal Classes
The following animal classes from the COCO dataset are supported:
- Dog
- Cat
- Bird
- Horse
- Sheep
- Cow
- Elephant
- Bear
- Zebra
- Giraffe

---

## Example
Input Image:  
![Sample_input_image](https://github.com/user-attachments/assets/4b0c85da-060d-4f8d-b75c-7a01d8cc12a9)
 

Detection Result:  
![Result_Image](https://github.com/user-attachments/assets/d76fe128-a692-4b31-9f88-2cc6175722d2)
 

---

## Notes
- Use high-resolution images for better detection accuracy.
- Ensure `yolov3.weights` and `yolov3.cfg` are properly downloaded and placed in the repository.

---

## License
This project is licensed under the [MIT License](LICENSE).

---

Feel free to modify this `README.md` file according to your preferences or additional details you might want to include!
