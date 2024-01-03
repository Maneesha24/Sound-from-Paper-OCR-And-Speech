# Image to Text to Speech Using Tesseract OCR and Python

This repository demonstrates the utilization of Optical Character Recognition (OCR) technology, specifically Tesseract OCR, along with Python to convert images containing text into machine-readable text formats. Furthermore, it showcases the subsequent conversion of this recognized text into speech using text-to-speech (TTS) technology.

## Introduction

Optical Character Recognition (OCR) serves as a potent tool for transforming various forms of text found in images into machine-readable formats. Beyond its primary function, integrating OCR with text-to-speech (TTS) or voice synthesis technology enables the conversion of recognized text into spoken words.

The association of OCR with sound dictation plays a pivotal role in enhancing accessibility for individuals with visual impairments or reading difficulties. This association, through screen readers or assistive technologies, facilitates users to listen to text-based content from documents, websites, or images, fostering inclusivity in education, employment, and daily life.

## Prerequisites
To utilize the code provided in this repository, ensure the following dependencies are installed:

- Tesseract OCR
- Python libraries: OpenCV (`cv2`), Pytesseract (`pytesseract`), gTTS (`gtts`)

Install these dependencies using the appropriate package manager or through Python's `pip`.

## Example

To run the provided script, make sure to replace `'./image_to_read.png'` with the path to your image file and adjust any language preferences (`lang='en'`) according to the desired language for text-to-speech conversion.

Execute the script and observe the extracted text output and the subsequent speech synthesis from the recognized text.

## Contributions

Contributions to enhance or expand the functionalities of this repository are welcomed! Feel free to open issues or pull requests for improvements, bug fixes, or additional features.
