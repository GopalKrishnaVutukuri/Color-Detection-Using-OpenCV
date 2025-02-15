# 🎨 Color Detection using OpenCV

## 📖 Overview
This project implements a **real-time color detection system** using **OpenCV and Python**. It allows users to click on an image and get the **closest matching color name** along with its **RGB values**. This is achieved by comparing the clicked pixel's RGB values with a predefined color dataset.

## 🚀 Features
- Detects **RGB values** of the clicked pixel.
- Matches the **closest color name** from a **color dataset (CSV file)**.
- Displays the detected color name and values on the image.
- Supports **real-time interaction** using mouse clicks.
- Works with **any image format (JPEG, PNG, WebP, etc.)**.

## 🛠️ Technologies Used
- **Python** 🐍
- **OpenCV** 👀 (for image processing)
- **Pandas** 📊 (for reading the color dataset)
- **NumPy** 🔢 (for efficient array handling)

## 📂 Project Structure



## 🔧 Installation & Setup

### **1️⃣ Install Dependencies**
Make sure you have **Python 3.7+** installed, then install the required packages:

bash
pip install opencv-python pandas numpy     


### **2️⃣ Clone the Repository
git clone https://github.com/your-username/color-detection.git
cd color-detection

3️⃣ Run the Project
python color_detection.py

💡 Note: If you're using Jupyter Notebook, replace cv2.imshow() with matplotlib.

🖱️ How to Use


Run the script and load an image.
Double-click anywhere on the image to detect the color.
The script will display:
Color name
RGB values
A color-filled rectangle overlay with text
Press ESC to exit.
🖼️ Demo Screenshot

📝 To-Do / Future Enhancements
 Add live webcam color detection 🎥
 Enhance the dataset for better accuracy 🏷️
 Support multiple color models (HSV, CMYK, etc.) 🎨
👏 Acknowledgments
OpenCV for powerful image processing tools.
Kaggle Dataset for color name mapping.
Special thanks to Programming Fever for the initial concept.

