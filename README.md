# CNN-model-for-Brachial-Plexus-Nerve-Trunks-Recognition-in-Ultrasound-Images
## Prerequisites
- Download Dataset: Download the dataset from the provided link (https://drive.google.com/file/d/1xMdKyX9k-Fi_vI5Tz-8qDDjFVn6iZGv4/view?usp=drive_link).
- Do not unzip. Locate Dataset in your Google Drive.
## Usage
- Open this repo (https://github.com/NHMSudara/CNN-model-for-Brachial-Plexus-Nerve-Trunks-Recognition-in-Ultrasound-Images.git) from Goolgle colab.
- Change the path of Dataset
```markdown
!unzip /path/to/new_data_nr.zip
```
- Run each and every block in notebook one by one. (make sure use GPU in Google Colab)
- After train the model, "inc_resUNet.h5" can be download.
## Model
### U-Net Architecture
The U-Net architecture is a convolutional neural network (CNN) designed for semantic segmentation tasks, especially in medical imaging. Introduced in 2015, it consists of an encoder, a decoder, skip connections, and a final layer. Key features include efficient use of training data, precise object localization, and adaptability to various imaging modalities. It's widely used for segmenting organs, tumors, and anatomical structures in medical images.
### Inc+ResU-Net Architecture
ResU-Net and Inception+U-Net are advanced adaptations of the U-Net architecture for medical image segmentation. ResU-Net utilizes residual blocks to mitigate vanishing gradients and enhance fine detail capture, while Inception+U-Net combines U-Net with Inception modules for improved multi-scale feature extraction and segmentation accuracy. The Inc+ResU-Net model, created by combining residual and Inception blocks, effectively addresses issues like vanishing gradients and enhances feature extraction.
![Inc+ResU-Net](https://github.com/NHMSudara/CNN-model-for-Brachial-Plexus-Nerve-Trunks-Recognition-in-Ultrasound-Images/blob/master/Inc+ResU-Net.png?raw=true)
## Contributing

We welcome 🤩 contributions from the community! If you'd like to contribute to this project, please follow these guidelines:

1. Fork the repository on GitHub.
2. Clone the forked repository to your local machine.
    ```bash
    git clone https://github.com/your-username/your-project.git
    ```
3. Create a new branch for your feature or bug fix.
    ```bash
    git checkout -b feature-name
    ```
4. Make your changes and commit them with descriptive commit messages.
    ```bash
    git add .
    git commit -m "Description of your changes"
    ```
5. Push your changes to your fork on GitHub.
    ```bash
    git push origin feature-name
    ```
6. Create a pull request from your fork to the original repository.
    - Include a detailed description of your changes in the pull request.
    - Be prepared to address any feedback or comments from the maintainers.

Thank you for contributing to improve model!
## Feedback

We value your feedback! If you encounter any issues, have suggestions for improvement, or would like to share your experience with our project, please don't hesitate to let us know.

- You can report issues or bugs by creating a new issue on GitHub.
- If you've found a bug and fixed it, or improve the model, we welcome pull requests! Please see the [Contributing](#contributing) section for more details.

Your feedback helps us improve our project and better meet the needs of our users. Thank you for your support!

