# OCR Web App with Keyword Search Functionality

## Objective
A web-based prototype that performs Optical Character Recognition (OCR) on uploaded images containing text in both Hindi and English. It also includes keyword search functionality to find and highlight specific terms in the extracted text. The application is accessible via a live URL.

---

## Features
1. **OCR Functionality:** Extracts text from uploaded images (JPEG, PNG, etc.) containing Hindi and English text.
2. **Keyword Search:** Allows users to search for keywords within the extracted text and highlights the results.
3. **User-Friendly Interface:** Built using Gradio for simplicity and ease of use.
4. **Live Deployment:** Accessible through a public URL for demonstration purposes.

---

## Technologies Used
- **Python Libraries:**
  - [Huggingface Transformers](https://huggingface.co/transformers/)
  - [PyTorch](https://pytorch.org/)
  - [Gradio](https://gradio.app/)
- **OCR Models:**
  - ColPali implementation of the new Byaldi library + Huggingface transformers for Qwen2-VL.
  - General OCR Theory (GOT), a 580M end-to-end OCR 2.0 model.
- **Deployment Platforms:**
  - Streamlit Sharing
  - Hugging Faces Spaces

---

## How to Run the Project

### 1. Environment Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ocr-keyword-search.git
   cd ocr-keyword-search
   ```
2. Create a Python virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### 2. Running the Application
1. Start the web application:
   ```bash
   python app.py
   ```
2. Open the provided local URL in your web browser to access the application.

---

## Application Workflow
1. **Upload Image:**
   - Users can upload an image containing Hindi and/or English text.
2. **Extract Text:**
   - The chosen OCR model processes the image and extracts text.
3. **Search for Keywords:**
   - Users enter a keyword to search within the extracted text.
   - Matching results are highlighted and displayed on the same page.

---

## Deployment
The application is deployed on [Platform Name] and accessible at: [Live URL]

### Deployment Steps
1. Prepare the application for deployment:
   ```bash
   pip install streamlit huggingface_hub
   ```
2. Deploy to the selected platform (e.g., Streamlit Sharing or Hugging Faces Spaces).
3. Verify that the application is live and functional.

---

## Directory Structure
```
ocr-keyword-search/
├── app.py                 # Main application script
├── requirements.txt       # Dependencies
├── README.md              # Project documentation
└── sample_images/         # Sample images for testing
```

---

## Future Enhancements
1. Support for additional languages.
2. Advanced text formatting in the output.
3. Improved keyword matching with fuzzy search.

---

## Acknowledgments
- [Huggingface Transformers](https://huggingface.co/transformers/)
- [PyTorch](https://pytorch.org/)
- [Gradio](https://gradio.app/)

---

## License
This project is licensed under the [MIT License](LICENSE).
