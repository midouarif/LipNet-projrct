# LipNet: Lip Reading with Deep Learning

## Overview
This project implements a lip reading system inspired by LipNet, which recognizes spoken words directly from video of lip movements. The model combines spatiotemporal CNNs, RNNs, and CTC loss to map video sequences to text.

## Tech Stack
- Python, TensorFlow/Keras  
- OpenCV for video preprocessing  
- NumPy, Pandas, Matplotlib  

## How to Run
1. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
2. Run the notebook:
   ```bash
   jupyter notebook LipNet.ipynb
## Results
The model demonstrates effective lip reading from video-only input. It shows how spatiotemporal CNNs combined with RNNs and CTC loss can handle sequence-to-sequence learning for visual speech recognition. Potential applications include accessibility tools for the hearing impaired and silent speech interfaces.

