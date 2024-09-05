# Detectron2 Image Object Detection

This project demonstrates how to use the [Detectron2](https://github.com/facebookresearch/detectron2) library for object detection on a single image using a pre-trained Faster R-CNN model. The image is processed to detect objects, and the result is visualized with bounding boxes.

## Requirements

To run this project, you'll need the following libraries installed:
- Python 3.x
- OpenCV
- Detectron2
- Matplotlib

You can install the necessary libraries using pip:
```
pip install opencv-python-headless detectron2 matplotlib
```

## Project Setup 

First, clone this repository:
```
git clone https://github.com/Fateme-zangane/Using-Detectron.git
cd Using-Detectron
```
Image Path:
Ensure you have an image file uploaded to your Google Colab environment if you're using Colab. You can adjust the path accordingly in the code if you're using your local machine.

Running the Code:
1-Load an image using OpenCV from the specified file path.
2-Use a pre-trained Faster R-CNN model from the Detectron2 model zoo.
3-Make predictions using the model.
4-Visualize the detected objects using the Visualizer from Detectron2 and Matplotlib.
```
python detectron_demo.py
```

Important Notes:
-The model uses a pre-trained Faster R-CNN network (faster_rcnn_R_101_FPN_3x) from the COCO dataset.
-The prediction threshold is set to 0.5, meaning that predictions with a confidence score below this value will be ignored.

## Output

The script will display the original image with bounding boxes around detected objects. The image will be shown using Matplotlib.

## File Structure 
```
Using-Detectron/
├── detectron_demo.py  # Main code for object detection
└── README.md          # This README file
```

## Troubleshooting
1-Image Not Found Error: If you see a FileNotFoundError, check if the image path is correct.
2-Detectron2 Installation Issues: Ensure Detectron2 is installed correctly following the [official installation guide](https://detectron2.readthedocs.io/en/latest/tutorials/install.html).

## License

This project is licensed under the MIT License.

## Contact

For any questions, please reach out to me via GitHub.







