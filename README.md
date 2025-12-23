**Image Processing & Data Representation Project**

📌 **Overview**
This project implements a from-scratch image processing system in Python to demonstrate data manipulation, computational thinking, and algorithm design—skills fundamental to Data Science. Instead of using high-level libraries like OpenCV, all transformations are applied directly at the pixel level, reinforcing understanding of matrices, iteration, and numerical computation.

**🛠️ Tech Stack**
Python
NumPy
PIL (for file I/O only — processing logic is fully custom)
Wave / Struct for audio data scaffolding

**🧠** Data Science Skills Demonstrated****
Structured data representation using nested lists (3D arrays)

Clean class design and abstraction (RGBImage, processing tiers)

Implementation of numerical algorithms

Cost-model simulation mimicking SaaS pricing logic

Robust validation, deep copying, and safe mutation practices

**🖼️ Core Features**
Base Processing
Negate
Grayscale
180° Rotation
Brightness Adjustment
Premium Processing
Block-based Pixelation
Edge Detection using convolution kernel
Tier System
Standard processor with cost + coupon system
Premium processor with advanced features

**▶️ Example Usage**

img = img_read_helper("input.png")

processor = StandardImageProcessing()

gray = processor.grayscale(img)

img_save_helper("output.png", gray)

**📂 Structure**

project.py

img/
  
  test + output samples

**👤 Author**
Nikita Jain
UC San Diego — Data Science
