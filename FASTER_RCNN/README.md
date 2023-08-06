#FASTER RCNN

## Step by Step

Prepare Dataset:
Download the COCO 2017 dataset, which contains images and annotations for various object classes, including "person."
Filter the dataset to keep only the samples labeled as "person." You can do this by creating a new subset of the dataset that includes only the images with person annotations.

Data Preprocessing:
Convert the filtered dataset to TFRecord format. TFRecord is a binary file format used by TensorFlow for efficient data loading during training.

Create Label Map:
Create a label map file that maps the class names to unique integer IDs. In this case, you will have only one class, which is "person."

Configuration File:
Create a model configuration file (usually in .config format) that defines the architecture and hyperparameters for your object detection model.

Training:
Use the TFOD API to train the model on the filtered dataset.
Start the training process using the TensorFlow Object Detection API's training script.
Monitor the training progress and adjust hyperparameters if needed.

Evaluation:
Evaluate the trained model on a validation set to measure its performance using metrics like mean Average Precision (mAP).

Inference:
Use the trained model for person detection on new images or videos

## Required Download Files
Please download the required files through the following link: https://drive.google.com/drive/folders/1jEpvZz0BCutAcqgJLj-PeATy7IRbuibf?usp=sharing

## Result
![image](https://github.com/zakky211/Object_Detection_with_YOLO_and_Faster_RCNN/assets/62234134/23205c48-7353-4b30-8a0d-bb4102b2fe5f)

## Evaluation

Loss Exploration
![image](https://github.com/zakky211/Object_Detection_with_YOLO_and_Faster_RCNN/assets/62234134/eb0565cb-578a-48c4-afa3-3d75e50f6526)

Learning Rate
![image](https://github.com/zakky211/Object_Detection_with_YOLO_and_Faster_RCNN/assets/62234134/831fb288-05f9-4373-9fe6-e072d6dfdcb6)




