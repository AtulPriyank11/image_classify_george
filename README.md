# image_classify_george
Project Overview

This project involves training an image classification model to detect the presence of St. George in images. We use a pre-trained EfficientNet-B0 model fine-tuned for this binary classification task.
# Data

Dataset Source: The images are obtained from two CSV files: georges.csv (containing images with St. George) and non_georges.csv (containing images without St. George).

# Dependencies

To run this project, you need to install the following dependencies. Create a requirements.txt file with the following content:

```bash
torch==2.0.1
torchvision==0.15.1
tqdm==4.65.0
pandas==2.0.3
scikit-learn==1.3.1
requests==2.31.0
pillow==10.0.0
```

Install these dependencies using:
```bash
pip install -r requirements.txt
```

I have GPU for training purposes. So for installing cuda to your system, refer the site and install as per your system requirements.
```bash                  
https://pytorch.org/get-started/locally/
```

Setup and Running the Project

1. Clone the Repository

```bash
git clone https://github.com/AtulPriyank11/image_classify_george.git
```

2. Refer the main.ipynb file and main docs.docx file.

3. Reasoning Behind Choices

Pre-trained Model: EfficientNet-B0 was chosen for its efficient performance on classification tasks. It is pre-trained on ImageNet, providing a solid foundation for transfer learning and reducing the need for extensive training data.


