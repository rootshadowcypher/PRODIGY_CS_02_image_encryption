# Image Encryption Tool

This project implements a simple image encryption tool using pixel manipulation techniques. By performing operations like swapping pixel values or applying mathematical operations to each pixel, the tool allows users to encrypt and decrypt images.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [License](#license)

## Introduction

This tool provides a basic approach to image encryption by manipulating pixel data. The encryption process involves modifying the pixel values of an image using custom algorithms, making it unreadable without the decryption process.

## Features

- Encrypts images using pixel manipulation.
- Decrypts images back to their original form.
- Supports basic mathematical operations and pixel value swapping.
- User-friendly interface for image selection and encryption/decryption options.

## Installation

To use this tool, you'll need Python and the required libraries installed on your system.

1. Clone this repository:
    ```bash
    git clone https://github.com/rootshadowcypher/image-encryption-tool.git
    ```

2. Navigate to the project directory:
    ```bash
    cd image-encryption-tool
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To use the Image Encryption Tool, follow these steps:

1. Run the Python script:
    ```bash
    python image_encryption.py
    ```

2. Select the image you want to encrypt or decrypt.

3. Choose the encryption or decryption method (e.g., pixel swapping, mathematical operation).

4. Save the resulting encrypted or decrypted image.

## Examples

### Encryption
Input: Original Image
- Operation: Pixel Swapping
- Result: Encrypted Image

### Decryption
Input: Encrypted Image
- Operation: Reverse Pixel Swapping
- Result: Decrypted Image (Original)


