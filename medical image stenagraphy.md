## 🧠 Medical Image Steganography - LSB & DCT Hybrid Technique

## 🔧 Description
Medical Image Steganography is a robust system for embedding audio (.wav) files into medical images (.dcm, DICOM format) using a hybrid approach of Least Significant Bit (LSB) and Discrete Cosine Transform (DCT) techniques. It ensures secure data communication by hiding audio in image pixels while preserving visual integrity

## 🚀 Features
-Upload and extract audio from DICOM medical images
-Dual embedding techniques: LSB (spatial) and DCT (frequency)
-Compute and compare image/audio quality using PSNR, SSIM, MSE, and SNR
-Visualize audio waveforms and spectrograms
-Interactive audio playback inside the notebook

## 🧪 Technologies Used
- Python (Colab / Jupyter Notebook)
- OpenCV
- NumPy, SciPy, Matplotlib, Pandas
- PyDICOM
- scikit-image (SSIM & PSNR)

## 🛠️ Setup Instructions

1. Clone the repo:
```bash
git clone https://github.com/your-username/medical-image-steganography.git
cd medical-image-steganography

```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Start MongoDB and run:
```bash
jupyter notebook steganography.ipynb
```

## 🗃️ Folder Structure

```
 steganography.ipynb       # Main notebook (Colab-compatible)
 README.md                 # Project overview and usage
 requirements.txt          # Python dependencies
.gitignore
```

## 📫 Contact
- Name: Shushma S
- Email: reddyshushma7@gmail.com
