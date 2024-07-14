## Sports Personality Classifier - Python Project with Flask UI

This project classifies images of five prominent sports personalities:

* Maria Sharapova
* Serena Williams
* Virat Kohli
* Roger Federer
* Lionel Messi

**Project Structure:**

* **UI:** Contains the website code for user interaction. (HTML, CSS, Javascript)
* **server:** Python Flask server handles communication between UI and model.
* **model:** Python notebook containing the machine learning model for classification.
* **google_image_scrapping:** Code to scrape images of the personalities from Google.
* **images_dataset:** Folder storing the downloaded image dataset.

**Technologies Used:**

* **Python:** Core programming language.
* **Numpy & OpenCV:** Libraries for image processing and manipulation.
* **Matplotlib & Seaborn:** Libraries for data visualization.
* **Scikit-learn (Sklearn):** Machine learning library for model building.
* **Jupyter Notebook:** Interactive environment for code development and model training.
* **Visual Studio Code/PyCharm:** Integrated Development Environments (IDEs) for coding.
* **Flask:** Python web framework for building the server.

**Project Functionality:**

* Scrape images from Google using the `google_image_scrapping` script. 
* Preprocess and clean the downloaded images in the `model` notebook.
* Train a machine learning model using Sklearn to identify the personalities. 
* Develop a Flask server (`server`) to handle user requests and communicate with the model.
* Design a user interface (`UI`) using HTML, CSS, and Javascript to allow users to upload images and receive classification results.

**Getting Started:**

1. Clone the project from your GitHub repository.
2. Install required libraries (`numpy`, `opencv-python`, `matplotlib`, `seaborn`, `scikit-learn`, `flask`). 
3. Run the `google_image_scrapping` script to download the initial dataset (optional: manually download images).
4. Open the `model` notebook in Jupyter Notebook and follow the instructions for training the model.
5. Run the Flask server (`python server.py`) to start the application.
6. Access the UI through a web browser (usually `http://127.0.0.1:5000/`).

**Acknowledgement:**

This project references learning materials from codebasics.io.


