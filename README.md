# Enhancement-of-Data-Security-Using-Cryptography-and-Steganography
This repository contains a project that demonstrates an integrated approach to data protection using RSA cryptography and LSB steganography, implemented in MATLAB.


1.	Overview:


    This project aims to improve data security by combining:

    •	Cryptography to encrypt sensitive information using the RSA algorithm.

    •	Steganography to hide encrypted data within an image using the Least Significant Bit (LSB) technique.

By layering encryption with data hiding, the system offers increased protection against unauthorized access and data breaches.


2.	Project Structure:



  RSA Cryptography

    •	Asymmetric encryption using a public/private key pair.

    •	Ensures data confidentiality even if intercepted.

  LSB Steganography

    •	Hides data in the least significant bits of an image.

    •	Used to conceal text or images without significant visual changes.

  Combined Approach

    •	Encrypts data using RSA.

    •	Embeds encrypted output inside a cover image via LSB.

    •	Provides a dual layer of security: cryptographic and visual concealment.


3.	Simulation Scenarios

    •	Text encryption and decryption using RSA.

    •	Image-in-image hiding using LSB steganography.

    •	Combined text and image encryption + steganography workflow.

All scenarios are executed and visualized using MATLAB.


4.	Results Summary

    •	RSA encryption securely encodes text messages(images 1.1,1.2,1.3).

    •	LSB technique successfully hides and recovers image data with minimal quality loss(Original image, image to hide, extracted hidden image).

    •	Combined model significantly enhances data security, albeit with a slight impact on performance(images 3.1,3.2,3.3).







