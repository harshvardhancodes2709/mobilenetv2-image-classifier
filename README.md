# mobilenetv2-image-classifier
An image classification web application built using Python, Streamlit, and MobileNetV2. Upload an image and get the AI model's top 3 predictions with confidence scores using a pretrained ImageNet model.

# MobileNetV2 Image Classifier

A simple AI-powered image classification web application built using **Python, Streamlit, and MobileNetV2**.

The application allows users to upload an image and uses a pretrained MobileNetV2 model to identify its contents. It displays the top 3 predictions along with their confidence scores.

## Features

- Upload images in JPG, JPEG, and PNG formats.
- Image preprocessing using OpenCV and NumPy.
- Uses pretrained MobileNetV2 with ImageNet weights.
- Displays the top 3 classification predictions.
- Shows confidence scores for each prediction.
- Caches the model to avoid loading it repeatedly.

## Technologies Used

- **Python** – Main programming language.
- **Streamlit** – Web application interface.
- **TensorFlow / Keras** – Deep learning framework and pretrained model.
- **MobileNetV2** – Image classification architecture.
- **OpenCV** – Image resizing and processing.
- **NumPy** – Numerical operations.
- **Pillow (PIL)** – Image handling.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/mobilenetv2-image-classifier.git
   ```

2. Navigate to the project directory:

   ```bash
   cd mobilenetv2-image-classifier
   ```

3. Install the required dependencies:

   ```bash
   pip install streamlit tensorflow keras opencv-python numpy pillow
   ```

## Usage

Run the following command in your terminal:

```bash
streamlit run main.py
```

The application will open in your browser.

1. Upload an image.
2. Click the **Classify Image** button.
3. Wait for the model to analyze the image.
4. View the top 3 predictions and their confidence scores.

## Model Information

This project uses **MobileNetV2**, a lightweight convolutional neural network pretrained on the ImageNet dataset.

The model uses transfer learning through pretrained ImageNet weights and predicts image categories without requiring additional model training.

## Project Structure

```text
mobilenetv2-image-classifier/
│
├── main.py
├── README.md
├── pyproject.toml
├── uv.lock
├── .python-version
└── .gitignore
```

## Future Improvements

- Add support for more image formats.
- Improve the user interface.
- Display prediction probabilities using visual charts.
- Add support for more classification models.

---

**Note:** This project is built for learning and exploring deep learning, computer vision, and image classification.
