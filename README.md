# OCR web app with keyword search functionality
A web-based prototype that demonstrates the ability to perform Optical Character Recognition (OCR) on an uploaded image (in picture format) containing text in both Hindi and English. This also includes additional keyword search functionality.

This project was done as a part of the assignment for Internship at PARIMAL Lab, IIT Roorkee. 

## Objective
Develop and deploy a web-based prototype that demonstrates the ability to perform Optical Character Recognition (OCR) on an uploaded image (in picture format) containing text in both Hindi and English. The web application should also implement a basic keyword search functionality based on the extracted text. The prototype must be accessible via a live URL.

## Scope of the Assignment
This assignment focuses on creating a web application that allows users to upload a single image, processes the image to extract text using OCR, and provides a basic search feature. The application must be deployed and accessible online.

# Tasks
## Task 1: Setup and OCR Implementation
### Environment Setup:
- Set up a Python environment with the necessary libraries, including Huggingface Transformers, PyTorch, and any other dependencies required for OCR.
- Explore the following OCR models and choose one to implement:
- ColPali implementation of the new Byaldi library + Huggingface transformers for Qwen2-VL.
- General OCR Theory (GOT), a 580M end-to-end OCR 2.0 model.
### OCR Model Integration:
- Implement the chosen OCR model to process a single uploaded image (JPEG, PNG, or other common picture formats) containing text in both Hindi and English.
- Ensure the model successfully extracts text from the image and returns the extracted text in a structured format (JSON or plain text).
## Task 2: Web Application Development
### Web Application:
- Develop a simple web application using Gradio or Streamlit.
- The application should allow users to:
- Upload an image file for OCR processing.
- Display the extracted text from the image.
- Enter keywords to search within the extracted text.
- Display search results on the same page, highlighting the matching sections.
## Task 3: Deployment
### Deploy the Web Application:
- Deploy the web application on platforms like Hugging Faces, Streamlit Sharing, or any other suitable platform.
- Ensure the application is accessible via a public URL.

