
# SAR Image Colorization for Comprehensive Insight Using Deep Learning

This repository contains the implementation of a **Deep Learning-based SAR Image Colorization system** developed for **Smart India Hackathon 2024**. The solution uses a **Hybrid Model combining Attention U-Net and Conditional GANs** to transform synthetic aperture radar (SAR) grayscale images into high-quality colorized images. This project aligns with the **Space Technology** theme to enhance the interpretation of SAR imagery for applications like disaster response, environmental monitoring, and climate change analysis.

---

## Key Features

- **Hybrid Model:** Combines the spatial feature extraction power of **Attention U-Net** with the realism of **Conditional GANs**.
- **Advanced Image Processing:** Overcomes noise issues, enhances fine-grained details, and generates realistic, visually intuitive outputs.
- **High Evaluation Metrics:** Achieved an average PSNR of **29.29 dB**, SSIM of **0.83**, and an average processing time of **1.44 seconds per image**.
- **Real-Time Feasibility:** Designed for integration into satellite systems for **real-time SAR image colorization**.

---

## Problem Statement

- **Problem Statement ID:** SIH1733
- **Title:** SAR Image Colorization for Comprehensive Insight using Deep Learning
- **Theme:** Space Technology
- **Category:** Software

---

## Technical Approach

### Model Architecture
1. **Attention U-Net:** Ensures precise spatial focus and better feature retention during colorization.
2. **Conditional GANs:** Enhances color realism by leveraging adversarial training techniques.

### Challenges Solved
- Mitigated intrinsic speckle noise in SAR images.
- Preserved fine-grained spatial and contextual features.
- Improved color consistency and realism.

### Workflow
1. Preprocessing: Image resizing, normalization, and noise mitigation.
2. Model Training: Custom loss functions integrating L1 loss, perceptual loss, and adversarial loss.
3. Post-Processing: Visual refinement and evaluation using PSNR and SSIM metrics.

---

## Benefits and Impact

### Key Advantages
- **30% Faster Data Interpretation:** Accelerates insights into SAR data.
- **Enhanced Disaster Response:** Provides improved visual data for critical decision-making.
- **20% Higher Accuracy:** Supports precise monitoring of environmental changes like deforestation and urbanization.

### NISAR Mission Impact
- Supports NASA-ISRO's **NISAR mission** by reducing SAR data interpretation time by 30%.
- Enhances public engagement with visually compelling SAR data visualizations.

---

## Results and Evaluation

- **PSNR:** 29.29 dB
- **SSIM:** 0.83
- **Processing Time:** 1.44 seconds per image

---

## Future Work

- Integration with satellite systems for **real-time colorization**.
- Expansion to **multi-spectral analysis** for broader applications.

---

## Repository Links

- [GitHub Repository](https://github.com/hackoverflow72/Team_HackOverflow_1733)
- [YouTube Demo](https://www.youtube.com/watch?v=BSW7WQf85j0)

---

## How to Run the Project

### Prerequisites
- Python 3.8 or later
- TensorFlow 2.x
- Other dependencies: See `requirements.txt` (to be added).

### Steps
1. Clone the repository:
    ```bash
    git clone https://github.com/hackoverflow72/Team_HackOverflow_1733
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Prepare the dataset:
    - Organize SAR grayscale images and corresponding optical images as specified in the `create_dataset` function.
4. Train the model:
    ```bash
    python train.py
    ```
5. Evaluate results:
    - Use pre-trained models provided or evaluate your trained models on test data.

---

## Contributions

Team HackOverflow thanks **Smart India Hackathon 2024** organizers for the opportunity to contribute to SAR image enhancement.

---

## References

- [Generating High-Quality Visible Images from SAR Images Using CNNs](https://www.researchgate.net/publication/323444158)
- [Colorizing Sentinel-1 SAR Images Using Variational Autoencoder](https://www.researchgate.net/publication/325470063)
- [SAR Image Colorization Using Multidomain CycleGAN](https://ieeexplore.ieee.org/document/8985381)

---

For more information, visit the project GitHub page and view the demo video.
