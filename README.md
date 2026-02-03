# Image-Blur-using-OpenCV-in-C
This project demonstrates how to apply various image blurring techniques using OpenCV in C. It includes implementations for Gaussian, Median, and Box (Mean) filters to reduce image noise and smooth details.


---

##  Features

- Load and process images using OpenCV.
- Apply and compare different types of blur:
  -  Gaussian Blur
  -  Median Blur
  -  Box (Mean) Blur
- View output results and understand their effects on image clarity.

---

##  Tech Stack

| Component  | Description       |
|------------|-------------------|
| Language   | C                 |
| Library    | OpenCV (C API)    |
| Platform   | CLI or Linux terminal |

---

##  Sample Output

> Original vs Blurred Images (comparison screenshots recommended here)

---

##  How to Run

###  Prerequisites

- GCC Compiler
- OpenCV installed (`opencv4` with C bindings)
- Any Linux-based environment or WSL (Windows Subsystem for Linux)

###  Compile

```bash
gcc blur_image.c -o blur_image `pkg-config --cflags --libs opencv4`
