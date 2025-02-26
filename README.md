# Steganography
This repository contains a simple image-based steganography project that allows users to hide and retrieve secret messages inside an image. The project uses OpenCV to modify pixel values and embed text securely. It also includes a PowerPoint presentation explaining the concept and implementation details.

-------------------------------------------------------------------------------------------------------------------------------------------


## Steganography - Hide Messages Inside Images
This repository provides a simple way to encrypt and decrypt messages inside an image using Python and OpenCV.

### Installation
To run this project, install the required library:

pip install opencv-python

### Usage

#### Encryption Process:

### Run the script:
python stego.py

Enter the secret message to be hidden.
Enter a passcode to protect the message.

The encrypted image (encryptedImage.jpg) will be generated.

#### Decryption Process:

Run the script again.
Enter the correct passcode.
The hidden message will be displayed.

### Working Mechanism 

The script reads the input image and modifies specific pixel values to store the ASCII values of the secret message.
The modified image is saved and can be opened like a normal image.
During decryption, the script reads the pixel values and reconstructs the hidden message if the correct password is provided.

### Files in this Repository
stego.py - Python script for encryption and decryption.
Image.jpg - Sample image used for hiding the message.
encryptedImage.jpg - Output image with the hidden message.
AICTE PPT Template.pptx - Presentation explaining the project.
