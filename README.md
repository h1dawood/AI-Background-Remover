# AI Background Remover

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Powered by: Transformers.js](https://img.shields.io/badge/Powered%20by-Transformers.js-blue)](https://huggingface.co/docs/transformers.js/index)
[![Model: briaai/RMBG-1.4](https://img.shields.io/badge/Model-briaai/RMBG--1.4-green)](https://huggingface.co/briaai/RMBG-1.4)

An advanced, free AI tool to remove and change image backgrounds with professional accuracy, running entirely in your browser. No server uploads, no privacy concerns.

---

## ✨ Features

*   **Client-Side AI Processing**: Utilizes the power of Transformers.js to run the AI model directly in the browser. This ensures user privacy as images are never uploaded to a server.
*   **High-Accuracy Model**: Employs the state-of-the-art `briaai/RMBG-1.4` model, which is designed to effectively separate foregrounds from backgrounds across various image types.
*   **Multiple Background Options**:
    *   **Transparent**: Get a clean PNG with a transparent background.
    *   **Solid Color**: Pick any color using a convenient color picker.
    *   **Gradient**: Choose from a selection of beautiful, predefined gradients.
    *   **Custom Image**: Upload your own image to use as the new background.
*   **Versatile Export Formats**: Download the final image in high-quality **PNG**, **JPG**, or **WebP** formats.
*   **Intuitive User Interface**: A modern, responsive interface with drag-and-drop support, a "Try an Example" option, and real-time status updates.
*   **Fast and Efficient**: The tool provides instant background removal without server latency.

## 🚀 How It Works

This application harnesses the power of modern web technologies and on-device machine learning to deliver a seamless experience:

1.  **Model Initialization**: On loading the page, the `briaai/RMBG-1.4` background removal model is downloaded and initialized using the Transformers.js library.
2.  **Image Input**: The user provides an image via drag-and-drop, file selection, or by using the provided example.
3.  **Client-Side Inference**: The AI model processes the image entirely within the user's browser. It analyzes the image and generates a precise mask that isolates the foreground subject.
4.  **Canvas Rendering**: The original image and the AI-generated mask are combined on an HTML canvas. The chosen background (be it transparent, a solid color, a gradient, or another image) is applied.
5.  **Instant Download**: The final composed image is displayed and made available for immediate download in the user's preferred format.

## 🛠️ Technology Stack

*   **AI/ML**:
    *   **[Transformers.js](https://huggingface.co/docs/transformers.js/index)**: A JavaScript library from Hugging Face that allows running cutting-edge AI models directly in the browser.
    *   **[briaai/RMBG-1.4](https://huggingface.co/briaai/RMBG-1.4)**: A highly accurate, state-of-the-art background removal model.
*   **Frontend**:
    *   **HTML5**: Structures the web application.
    *   **CSS3**: Provides the modern, responsive, and animated design.
    *   **Vanilla JavaScript (ES Modules)**: Powers the application's logic, from UI interactions to AI processing.

## Usage

To use the tool, simply open the `index.html` file in any modern web browser.

1.  **Upload Image**: Click the upload area or drag and drop an image file onto it. Alternatively, click "Try an example" to test the tool with a sample image.
2.  **Processing**: Wait a few moments while the AI model processes the image. Status updates will be displayed.
3.  **Customize Background**: Once processing is complete, a control panel will appear. Choose from Transparent, Solid Color, Gradient, or a custom Image background.
4.  **Apply Changes**: Click the "Apply Changes" button to see your new background.
5.  **Download**: Select your desired format (PNG, JPG, or WebP) and click the "Download Image" button.

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](https://opensource.org/licenses/MIT) file for details.

**Note**: The `briaai/RMBG-1.4` model is available for non-commercial use under its own license. For commercial applications, a license must be purchased from BRIA AI.
