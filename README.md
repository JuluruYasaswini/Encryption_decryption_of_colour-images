# Encryption_decryption_of_colour-images
# Colour Image Encryption Decryption Algorithm Based on the novel 2D Logistic Cos-Sine Maps

This MATLAB project demonstrates image encryption using chaotic maps, specifically two-dimensional Logistic cosine-sine maps. The algorithm encrypts and decrypts RGB channels of an image using three encryption keys generated from chaotic sequences.

## Getting Started

### Prerequisites

- MATLAB installed on your computer
- You can work in MATLAB online tool(if not installed)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/image-encryption.git
   cd image-encryption
2. Open MATLAB and navigate to the project directory.
3. Encryption:
   
        Open MATLAB and run the encryption_script.m file.
        The script downloads an example image from a URL, resizes it to specified dimensions (256x256), and performs the following steps:
        Initializes chaotic map parameters (mu1, mu2, gamma1, gamma2).
        Encrypts the image RGB channels using chaotic maps and bitwise XOR operations with encryption keys (key1, key2, key3).
        Saves the encrypted image (cimage2) and encryption keys to a file named yashproject.mat.
   
5. Decryption:

      To decrypt the encrypted image, run the decryption_script.m file.
      The script loads the encrypted image (cimage2) and performs decryption using the same chaotic maps and encryption keys (key1, key2, key3).
      Displays the original and decrypted RGB channels and combines them into a final decrypted image (cimage3).
   
6.Correlation Coefficient Analysis
      Run the correlation_coefficient.m script to analyze correlation coefficients between pixel values of the original and encrypted images in horizontal, vertical, and diagonal directions.
      Plots are generated to visualize pixel correlations.

7. Entropy Calculation
      Run the entropy_calculation.m script to calculate and compare the entropy of CIELAB channels (Cr, Cg, Cb) of the encrypted image (cimage2).
      Displays the entropy values in a bar chart.

8.Contributing
      Contributions to improve the project are welcome. Please fork the repository, make your changes, and submit a pull request.
