

# Text Extraction from Diagram using Gemma 2B

This project is a Jupyter Notebook–based application that allows users to **extract text and contextual information from diagrams or tables** using OCR, OpenCV, and the Gemma 2B model. It provides a simple UI where users can upload an image and get structured results.

##  Features

* Upload images containing **tables or diagrams**
* Choose input type via radio buttons (Table / Diagram)
* Perform **OCR-based text extraction**
* Detect **shapes, arrows, and associations** in diagrams
* Generate a **natural language explanation** of the extracted content using Gemma 2B
* User-friendly interface built with Gradio

##  Screenshots

###  Home Display  
Upload an image and select whether it is a table or a diagram.  
![Home Display](images/SC01.png)

###  After Upload  
Once the image is uploaded, processing begins.  
![After Upload](images/sc02.png)

###  Results Window  
Processed results with text, arrows, and contextual mapping.  
![Results Window](images/SC03.png)

###  Results Fullscreen  
Full-screen display of extracted text and diagram interpretation.  
![Results Fullscreen](images/SC04.png)

##  Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. Install required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook "Text_Extraction_from_diagram_using_gemma_2b.ipynb"
   ```

##  Usage

1. Run all cells in the notebook.
2. The **Gradio interface** will launch.
3. Upload an image (table or diagram).
4. Select the image type via radio button.
5. View extracted text and interpretation on screen.

##  Tech Stack

* **Python**
* **Gradio** (UI)
* **OpenCV** (image preprocessing & shape detection)
* **Tesseract OCR** (text extraction)
* **Gemma 2B** (LLM-based explanation generation)

##  Future Improvements

* Add support for **handwritten diagrams**
* Enhance table structure recognition
* Improve diagram-to-graph conversion
* Export results as **structured JSON / CSV**


