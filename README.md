# 📸 ResNet50 Image Tag Prediction Web App with Gradio

This project demonstrates how to build a **real-time image classification web application** using a pre-trained **ResNet50** model from TensorFlow and the user-friendly interface tool **Gradio**. Users can upload any image, and the model will predict the top 5 possible objects or tags in the image along with their confidence scores.

## 🎯 Project Overview

This web app is designed to allow users to:
- Upload an image.
- Receive real-time predictions using the ResNet50 model.
- View the top 5 predicted tags with confidence levels.
  
The app uses the **ResNet50 model** trained on the **ImageNet dataset**, which includes over 1,000 object categories. The predictions are made in real time, and the app interface is built using **Gradio**, which provides an easy-to-use, accessible web interface.

![Example Prediction](https://user-images.githubusercontent.com/yourimagepath/example_image.png)

## 🚀 Features
- **Real-time Image Classification**: Upload an image and get instant predictions.
- **Pre-trained ResNet50 Model**: Leverages the power of a pre-trained deep learning model.
- **Top 5 Predictions**: The app provides the top 5 most likely tags for any image.
- **Gradio Interface**: Simple and intuitive user interface, making it easy to run locally or in the cloud (e.g., Colab).
  
## 🛠️ Tech Stack
- **Python**: The core language for development.
- **TensorFlow**: For loading and using the ResNet50 model.
- **Gradio**: For building an interactive web interface.
- **Colab**: Optionally use Google Colab to run the project without local setup.

## 🔧 How to Run the Project

### Step 1: Clone the Repository
```bash
git clone https://github.com/yourusername/resnet50-image-tag-prediction.git
cd resnet50-image-tag-prediction
```

### Step 2: Install Dependencies
```bash
pip install -r requirements.txt
```

### Step 3: Run the App
```bash
python app.py
```

Once the app is running, Gradio will launch a local server or provide a link to access the app on your browser.

### Step 4: Use Google Colab (Optional)
You can also run this project directly in **Google Colab**. Simply open the `Colab Notebook`, upload the code, and run the cells to launch the web app via an **ngrok** link.

## 📊 Example Results

Upload an image, and the app will display the top 5 tags with their respective probabilities. 

### Input Image:
![Input Example](https://user-images.githubusercontent.com/yourimagepath/input_image.png)

### Predicted Tags:
```
1. Tabby cat: 89.23%
2. Tiger cat: 5.01%
3. Egyptian cat: 2.75%
4. Lynx: 1.33%
5. Cougar: 0.89%
```

## 📁 Files in the Repository

- `app.py`: Main Python file that runs the Gradio interface.
- `model.py`: Contains the code for loading the ResNet50 model and processing images.
- `requirements.txt`: Lists the dependencies for the project.
- `README.md`: This documentation file.

## 👥 Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue.
