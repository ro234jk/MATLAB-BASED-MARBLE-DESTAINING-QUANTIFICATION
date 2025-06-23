# 🧼 MATLAB-Based Marble Destaining Quantification

This project provides a MATLAB-based tool for **automated stain detection** and **quantitative evaluation** of cleaning effectiveness on marble or stone surfaces. The process compares "before" and "after" images using color-based segmentation in HSV space to objectively measure stain reduction.

---

## 🔍 What This Project Does

This tool enables:

- **Detection of stains** based on predefined HEX color codes converted to HSV.
- **Pixel-level segmentation** to isolate stained regions from the background.
- **Quantitative measurement** of stained area before and after cleaning.
- **Retry logic** if stain detection fails due to low contrast or lighting variation.
- **Visualization** of both original images and their corresponding stain masks.

This is particularly useful for researchers and practitioners in:
- Heritage conservation
- Civil engineering material evaluation
- Automated visual inspection tasks

---

## 📁 Repository Contents

- `main_script.m` – Main execution script
- `createColorMask.m` – Custom HSV-based stain segmentation function
- `example_before.jpg` – Sample image before cleaning and after cleaning
- `README.md` – Documentation and usage instructions

---

## 🛠️ Requirements

- **MATLAB R2024a**
- **Image Processing Toolbox**

Also tested on:  
✅ MATLAB R2019b and later

---

## 💻 How to Use in MATLAB

### Step 1: Download the Code

- Clone the repository:
  ```bash
  git clone https://github.com/ro234jk/MATLAB-BASED-MARBLE-DESTAINING-QUANTIFICATION.git
