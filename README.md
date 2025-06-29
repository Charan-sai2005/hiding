# # 🖼️ Image Steganography Using Python

This project demonstrates how to hide secret messages inside images using **Least Significant Bit (LSB) steganography**.

## 📂 Files Included

- `Image_Steganography_Project.ipynb` – Jupyter Notebook with full step-by-step code
- `input.png` – Sample input image used for encoding
- `stego_image.png` – Output image with hidden message (generated during runtime)

## 🛠️ Requirements

- Python 3
- Pillow (`pip install pillow`)

## 🚀 How to Use

1. Open `Image_Steganography_Project.ipynb` in Jupyter or Google Colab.
2. Run all cells in order:
   - Install libraries
   - Define encode/decode functions
   - Encode a secret message
   - Decode and view the hidden message

## 💡 How It Works

This project modifies the **least significant bits (LSBs)** of the RGB pixel values to hide message bits. It's a simple form of image steganography that doesn't visibly alter the image.

## 📌 Author

- Charan
