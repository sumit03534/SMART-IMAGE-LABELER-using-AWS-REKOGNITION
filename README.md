# SMART-IMAGE-LABELER-using-AWS-REKOGNITION
The Image Labeler using Amazon Rekognition is a cloud-based application that automatically detects and labels objects in images. It uses Amazon S3 for image storage and integrates with Rekognition. The system generates labels with confidence scores, enabling accurate image classification.


<img width="1920" height="1080" alt="AWS Rekognition" src="https://github.com/user-attachments/assets/09121557-41ca-4b46-8bde-b3341e2f18bd" />
YouTube Video Link: https://youtu.be/jIjTx5RMat4


In this project, we will be building an image labels generator, using Amazon Rekognition. This is going to be a fun one. Once built, it will be able to recognize and label images. For example, if you have a photo of a cat, Amazon Recognition will be able to identify what it is, and label the image as a cat.

### Steps to be performed:
We'll be going through the following steps.

* Creating an Amazon S3 Bucket: image-labeler-using-amazon-rekognition-bucket
* Uploading images to the S3 Bucket
* Installing configuring the AWS Command line interface (CLI)
* Importing libraries
* Adding detect_labels function
* Adding main function
* Running your python file

### Services Used 🛠
* Amazon S3: For storing the images in the process of generating labels.
* Amazon Rekognition: To analyse images and generate image labels.
* AWS CLI: Interacting with AWS services through command line interface(CLI).

### Estimated Time & Cost ⚙️
* This project is estimated to take about 20-30 minutes
* Cost: Free (When using the AWS Free Tier)

### Project Architecture: 
<img width="1607" height="808" alt="Architect" src="https://github.com/user-attachments/assets/a099a93b-732f-4a76-9da2-556fa5caf62b" />



