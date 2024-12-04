# Crop and Weed Detection System Using CNN

## Overview  
This project focuses on building a **Crop and Weed Detection System** using Convolutional Neural Networks (CNN). The system helps farmers optimize pesticide usage by detecting and differentiating crops and weeds in agricultural fields, ensuring pesticides are sprayed only on weeds, minimizing waste, and preventing crop contamination.

---

## Features  
- **Accurate Weed Identification**: Utilizes a trained CNN model to classify crops and weeds.  
- **Optimized Pesticide Usage**: Reduces pesticide waste and environmental impact.  
- **Improved Crop Health**: Minimizes the mixing of pesticides with crops, improving crop yield and quality.

---

## Project Architecture  
1. **Dataset Preparation**  
   - The system uses a labeled dataset containing images of crops and weeds.  
   - Images are preprocessed, including resizing, normalization, and augmentation, to improve model performance.

2. **Model Training**  
   - A CNN architecture was designed and trained on the dataset.  
   - The model learns to classify images as either crop or weed.  
   - Tools: TensorFlow/Keras or PyTorch.

3. **Prediction System**  
   - Deployed as an application (web or desktop) that takes images from the field as input and outputs predictions.  
   - Results guide spraying devices for precision targeting.

---

## Technical Stack  
- **Programming Language**: Python  
- **Deep Learning Framework**: TensorFlow/Keras or PyTorch  
- **Dataset**: Custom dataset or publicly available agricultural image datasets  
- **Tools & Libraries**: OpenCV, NumPy, Matplotlib, Pandas

---

## Setup and Installation  

### Prerequisites  
- Python 3.7 or later  
- TensorFlow/Keras or PyTorch installed  
- Virtual environment for dependencies (optional but recommended)

### Steps  
1. Clone the repository:  
   ```bash
   git clone <repository-url>
   cd crop-weed-detection
   ```
2. Install required dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Prepare the dataset:  
   - Place images in the `dataset/` directory.  
   - Follow the folder structure:  
     ```
     dataset/
         crops/
         weeds/
     ```

4. Train the model:  
   ```bash
   python train_model.py
   ```

5. Test the model:  
   ```bash
   python test_model.py
   ```

6. Run the application:  
   ```bash
   python app.py
   ```

---

## Usage  

1. Capture images of agricultural fields using a camera or drone.  
2. Input the images into the system.  
3. The model predicts whether the image section contains a crop or weed.  
4. Use the results to guide pesticide spraying devices.


---

## Future Scope  
- Integration with IoT devices for automated field scanning.  
- Real-time detection using edge devices.  
- Expanding the system to detect multiple types of weeds and crops.

---

## Contributors  
- **Tanishq Kokane**  

