# Handwritten Captcha Detector 

## Overview

It is a machine learning program designed to convert handwritten captchas composed of English letters and emojis mapped to numbers into plain text. The program utilizes deep learning techniques and convolutional neural networks, leveraging the power of OpenCV for image processing.

## Demonstration
![Demo GIF](https://github.com/Komal2531/Handwritten-Captcha-Solver/blob/master/Application%20Demo/captcha_web_demo.gif)

## Captcha Components

- **Emojis**: Captchas may contain the following emojis, each mapped to a specific number:
    - Checkmark (✅): 1
    - Cloud (☁️): 2
    - Croissant (🥐): 3
    - Heart (❤️): 4
    - Laugh (😄): 5
    - Smile (😊): 6
    - Sun (☀️): 7

- **Letters**: Captchas may contain the following English letters:
    - A, B, C, D, E, F, G, H, J, K, M, P, R, T, W, X, b, e, h

## Approach

### Segmentation of Letters
- Utilized OpenCV for image processing, leveraging the `img_cleaning()` and `read()` segmentation code.
- Successfully extracts letters from both digital and handwritten images.
- Proficient in reading colorful images, handling shadows, and mitigating the impact of noise.

### Model Training
- Utilizes Convolutional Neural Networks (CNN) for efficient learning.
- Evaluates loss using Cross Entropy loss, ensuring effective model training.
- Optimizes model parameters using the Adam optimizer for rapid convergence.


