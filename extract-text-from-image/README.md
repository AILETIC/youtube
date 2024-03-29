Certainly! Here's an updated version of the README file:

# Image to Text Converter

This repository contains a Python script that extracts text from images using Optical Character Recognition (OCR) technology. It utilizes the Tesseract OCR engine and OpenCV library to process images and convert them into text.

## Getting Started

To get started with this project, follow the steps below:

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/AILETIC/youtube.git
   ```

2. Navigate to the project directory:

   ```
   cd youtube/extract-text-from-image
   ```

3. Create a virtual environment:

   - For macOS/Linux:

     ```
     python3 -m venv env
     ```

   - For Windows:

     ```
     python -m venv env
     ```

4. Activate the virtual environment:

   - For macOS/Linux:

     ```
     source env/bin/activate
     ```

   - For Windows:

     ```
     .\env\Scripts\activate
     ```

5. Upgrade pip:

   - For macOS/Linux:

     ```
     pip3 install --upgrade pip
     ```

   - For Windows:

     ```
     pip install --upgrade pip
     ```

6. Install the required dependencies:

   - For macOS/Linux:

     ```
     pip3 install -r requirements.txt
     ```

   - For Windows:

     ```
     pip install -r requirements.txt
     ```

7. Run the main or convert script:

main.py:

   - For macOS/Linux:

     ```
     python3 main.py
     ```

   - For Windows:

     ```
     python main.py
     ```

convert.py: 

   - For macOS/Linux:

     ```
     python3 convert.py -f "jpg"
     ```

   - For Windows:

     ```
     python convert.py -f "jpg"
     ```


## Usage

The main script (`main.py`) performs the following steps:

1. Retrieves a list of image file paths from a specified directory.
2. Converts the images into RGB format.
3. Extracts text from the images using Tesseract OCR.
4. Saves the extracted text as a text file and as a PDF.

You can modify the script to suit your specific requirements, such as changing the input directory or language settings.

## Contributing

Contributions to this project are welcome. If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to customize this README file according to your needs. Let me know if there's anything else I can help you with!
