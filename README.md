# PaveNet
PaveNet: An Architecture for Multi-class semantic segmentation in Urban Environments

# Authors:
Sahish Ashok Pandav<br />
Om Tidke<br />
Madhura Pande<br />


# Overview
PaveGuard is a cutting-edge solution aimed at enhancing urban environment image segmentation using a novel UNet architecture. This project leverages deep residual networks combined with the powerful UNet model to achieve multi-class segmentation of street images. The lightweight design of the model makes it suitable for embedded systems, where efficient computation and high precision are required.

# Key Features:
High accuracy of 88.9%.
Mean Intersection over Union (mIoU) of 51.19.
Optimized for embedded systems with limited resources.
Effective in real-time applications like autonomous vehicles and delivery robots.
Dataset
The project utilizes the CamVid dataset, which contains:

700+ annotated images.
32 semantic classes of urban elements (buildings, traffic signs, trees, etc.).
For more information about the dataset, visit: CamVid

# Methodology
The Enhanced ResUNet architecture is built on the traditional UNet model with improvements using Residual Learning. This results in a more lightweight and accurate model for image segmentation tasks in urban settings.

## The architecture consists of three major parts:

1. Encoder
2. Bridge
3. Decoder

![image](https://github.com/user-attachments/assets/a4337bd7-dc96-4644-a72d-53fb20bc337b)

Results
Training Accuracy: 97.76%
Validation Accuracy: 88.88%
Mean IoU: 51.19

# Training and Validation Curves
![image](https://github.com/user-attachments/assets/ee6bb58d-ed4a-4055-8710-ab4be642a607)
![image](https://github.com/user-attachments/assets/f4939858-14e2-4ca5-aa2e-bd340c4fcf55)

Below are some results from the CamVid dataset:


Original Image<br />
![image](https://github.com/user-attachments/assets/fe645f97-e583-47a3-abbc-bde60b04179a)<br />
Annotated Image<br />
![image](https://github.com/user-attachments/assets/bb8fd3f9-d356-44a3-a44e-6a47171854c9)<br />


# Segmentation Results
![image](https://github.com/user-attachments/assets/e9350a54-5a7a-4695-b7cf-60a655d0ca96)
![image](https://github.com/user-attachments/assets/c382e89a-771c-4ac2-b86a-887e4261801c)
![image](https://github.com/user-attachments/assets/6ba0f43b-3838-416b-8bb5-4274141c505b)

Future Work
We aim to further optimize the architecture and explore additional datasets to improve the model's generalization capabilities. In particular, we plan to fine-tune hyperparameters and investigate better data augmentation techniques to enhance segmentation accuracy.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Code Availability
The source code for the project is not included in this repository. For access to the code, please contact the author via email.

Contact
If you have any questions or need further assistance, feel free to reach out:

Author:
Email: om.b.tidke@gmail.com
Email: sahishpandav@gmail.com

We hope you find this project useful. If you do, don't forget to ⭐ star the repository!

