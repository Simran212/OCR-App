# OCR Project

This project focuses on Optical Character Recognition (OCR) to extract text from images.

## Overview

The OCR project is aimed at extracting textual information from images or scanned documents. It utilizes [insert technology/library/tool name] to perform character recognition and convert images into editable text.

## Features

- Image preprocessing for better OCR results.
- Character recognition and extraction from images.
- Support for multiple file formats (e.g., JPEG, PNG, PDF).
- Listing all existing OCR uploads
- Deleting an existing OCR

## Installation

1. Clone the repository :
gh repo clone Simran212/OCR-App

2. Start the backend server
   cd idocr-backend
   node index.js

3. Start the frontend server
   npm run dev

4. Go to the directed URL by Vite which will be your localhost url and then you can use the App from the User Interface


Here I'll be attaching some screenshots showcasing the working of the project



An Image upload can be facilitated by choosing a file and clicking on the upload button.


<img width="729" alt="Screenshot 2023-12-25 at 11 42 46 PM" src="https://github.com/Simran212/OCR-App/assets/69590139/21e93fc0-8238-46cf-8dcf-1bd390311484">





After the Google Vision API processes the image received it returns the extracted information in form of a json formatted response.


<img width="698" alt="Screenshot 2023-12-25 at 11 44 24 PM" src="https://github.com/Simran212/OCR-App/assets/69590139/4ef4f882-1820-4453-910e-f05446c3156a">


You can also list all the existing extracted OCR JSON(s), just click on the List OCRs button !

<img width="896" alt="Screenshot 2023-12-25 at 11 45 24 PM" src="https://github.com/Simran212/OCR-App/assets/69590139/f07355a0-82a8-4d0a-a72a-f1ad234397c7">
