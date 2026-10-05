# IVA – Interactive Vision Analysis

IVA (Interactive Vision Analysis) is a web-based image processing application built using **Python, Streamlit, OpenCV, NumPy, and Pillow**. It provides an interactive interface for uploading images and applying different image processing and computer vision techniques.

## 🚀 Live Demo

**Streamlit App:**
https://iva-interactive-vision-analysis.streamlit.app/

## 📌 Features

* Upload and process images directly in the browser
* Supports common image formats such as:

  * PNG
  * JPG
  * JPEG
* Image visualization and analysis
* Grayscale image conversion
* Spatial domain image processing
* Image filtering
* Edge detection
* Image sharpening
* Interactive results display
* Simple and user-friendly interface

## 🛠️ Image Processing Techniques

IVA includes several commonly used image processing operations:

### 1. Mean Filter

A smoothing filter that reduces noise by replacing each pixel with the average value of its neighboring pixels.

### 2. Median Filter

A noise-reduction technique that replaces a pixel with the median value of its neighborhood. It is especially useful for removing salt-and-pepper noise.

### 3. Gaussian Filter

A smoothing technique that uses a Gaussian kernel to reduce image noise and small details.

### 4. Sobel Operator

The Sobel operator detects edges by calculating intensity changes in horizontal and vertical directions.

* Sobel X
* Sobel Y

### 5. Prewitt Operator

Prewitt is an edge detection technique used to identify horizontal and vertical edges in an image.

### 6. Roberts Operator

Roberts detects edges using small convolution kernels and is useful for detecting diagonal changes in intensity.

### 7. Laplacian Operator

The Laplacian operator detects rapid changes in image intensity and is commonly used for edge detection.

### 8. Sharpening

The sharpening operation enhances edges and fine details, making the image appear clearer.

## 💻 Technologies Used

| Technology | Purpose                         |
| ---------- | ------------------------------- |
| Python     | Core programming language       |
| Streamlit  | Web application framework       |
| OpenCV     | Image processing                |
| NumPy      | Numerical and matrix operations |
| Pillow     | Image handling                  |
| TensorFlow | Deep learning support           |
| DeepFace   | Face analysis functionality     |

## 📂 Project Structure

```text
iva-interactive-vision-analysis/
│
├── app.py
├── requirements.txt
├── packages.txt
└── README.md
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/rithanya73/iva-interactive-vision-analysis.git
```

### 2. Navigate to the project directory

```bash
cd iva-interactive-vision-analysis
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the virtual environment

**Windows PowerShell:**

```powershell
venv\Scripts\Activate.ps1
```

### 5. Install the dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the application

```bash
streamlit run app.py
```

The application will open in your browser.

## 📦 Requirements

The project uses the following main dependencies:

```text
streamlit
numpy==1.26.4
Pillow
opencv-python-headless==4.10.0.84
deepface==0.0.101
tensorflow==2.20.0
tf-keras==2.20.1
```

## 🌐 Deployment

IVA is deployed using **Streamlit Community Cloud**.

The application can be accessed here:

https://iva-interactive-vision-analysis.streamlit.app/

## 🔄 How It Works

```text
Upload Image
      ↓
Image Preprocessing
      ↓
Select Image Processing Technique
      ↓
Apply Processing Operation
      ↓
Display Processed Image
      ↓
Analyze / Compare Results
```

## 🎯 Project Objective

The main objective of IVA is to provide an easy-to-use interactive platform for understanding and experimenting with fundamental image processing techniques.

Instead of processing images only through Python code, IVA provides a visual interface where users can upload an image, select an operation, and immediately observe the processed result.

## 👩‍💻 Developed By

**Rithanya**

BCA – Computer Applications

## 📄 License

This project is created for educational and academic purposes.
