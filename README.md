# My_project1
<h1>OCR-based Answer Recognition and Scoring System</h1>
<h2>Overview</h2>
This project is an Optical Character Recognition (OCR) model that processes images containing answers, recognizes characters, and matches them with predefined correct answers stored in the form of a dictionary. Based on the matched answers, a score is calculated and provided as output.

The system can be used for automatic answer grading or any scenario where you need to compare handwritten or printed answers with predefined responses.

<h2>Features</h2>
OCR Model: Utilizes OCR to extract text from images.
Answer Matching: Matches recognized text against predefined correct answers stored in a dictionary.
Scoring System: Provides a score based on the accuracy of the matched answers.
Image Inputs: Accepts images of handwritten or printed answers.
Output: Displays the score and the comparison of recognized and correct answers.

<h2>Requirements</h2>
Before running the project, ensure you have the following installed:

Python 3.x<br>
Libraries:<br>
1. pytesseract: For Optical Character Recognition (OCR).<br>
2. opencv-python: For image processing.<br>
3. numpy: For array and matrix operations.<br>
4. Pillow: For image handling.<br>
5. matplotlib: For plotting and visualizing images (optional, for debugging).<br>

<h3>You can install the required libraries using pip:</h3>
pip install pytesseract opencv-python numpy Pillow matplotlib

<h2>Setup</h2>

1. <b>Clone the repository</b>:<br>
bash command:
git clone https://github.com/username/ocr-answer-recognition.git <br>
cd ocr-answer-recognition<br>

2. <b>Install dependencies</b>: If you're using a virtual environment, make sure it's activated, then install the dependencies listed above.

3. <b>Prepare your images</b> : Add images of the answers (handwritten or printed) into the images folder in your project directory. Ensure that the images contain the answers that need to be matched against predefined answers.

4. <b> Predefined answers </b>: The correct answers are stored in a dictionary in the answers.py file, which maps questions or answer keys to the correct responses. You can modify this file to add or update answers.

<h2>Usage</h2>
To run the OCR model and compare answers with predefined solutions, execute the following Python script:<br>

bash<br>
python main.py<br>
<h3>The script will:</h3>

1. Process each image from the images folder.
2. Extract the recognized text using OCR.
3. Match the extracted text with the predefined answers.
4. Calculate a score based on the number of correct matches.
5. Output the score along with the recognized answers and comparison results.

<h3>Example output format:</h3>
![Screenshot 2024-12-16 125921](https://github.com/user-attachments/assets/2f894de6-e1de-4109-8d18-5a64c247c648)

<h3>Dictionary Format for Predefined Answers</h3>
answers = {
    "Q1": "Python programming",
    "Q2": "Machine learning",
    "Q3": "Data science",
    # Add more questions and answers as needed
}

<h2>Contributing</h2>
If you would like to contribute to this project, please fork the repository, make your changes, and create a pull request. Contributions are always welcome!

<h2>License</h2>
This project is licensed under the MIT License - see the LICENSE file for details.

   
