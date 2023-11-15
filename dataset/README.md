# Surgical Instruments Dataset

## **Overview**  
The Surgical Instruments Recognition Dataset is a groundbreaking collection of high-resolution images (1280x960 pixels) specifically designed for the recognition and categorization of surgical instruments. This dataset captures the intricate details and complexity of surgical tools, particularly when arranged in scenarios reminiscent of an operating room.

## **Data Acquisition**

Our data collection approach was multifaceted to encompass a wide range of scenarios in which surgical instruments are typically viewed. We utilized:
1. **Ceiling-mounted, program-controlled camera:** This camera systematically rotated to capture the instruments from various angles.
2. **Handheld camera:** It was employed to take pictures of instruments in trays on the floor, creating images with natural shadows and lighting.
3. **Real-world operating room imagery:** We included close-up shots of instruments in use, offering a view akin to that of the surgical team, and capturing the tools in motion.

## **Annotations**  
The dataset adheres to the COCO results format, supporting object and keypoint detection tasks. For object detection, bounding boxes and class labels are provided for each instrument. Key point annotations identify precise instrument points, with over 10,000 key points annotated throughout the dataset.

## **Dataset Structure**  
The dataset is divided into three parts: 
- Training set: 1789 images
- Validation set: 200 images
- Testing set: 185 images

This structure is designed for comprehensive model training, fine-tuning, and unbiased evaluation of the model's performance on new data.
