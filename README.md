# **Malicious URL Detector**

This project provides a tool for detecting malicious URLs using machine learning. It includes a Jupyter notebook for feature extraction and model training, and a Tkinter-based graphical user interface (GUI) for user interaction.

### **Files**

**Mal_URL.ipynb**: This notebook handles the feature extraction and classification of URLs using a trained machine learning model.

**URL_UI.ipynb**: This notebook provides a simple GUI for the Malicious URL Detector, allowing users to input URLs and receive predictions on whether the URL is benign or malicious.

### **Requirements**

Python 3.6+ 

Jupyter Notebook

**Required Python Libraries:**

pandas

numpy

scikit-learn

tldextract

tld

tkinter

### **Usage**

**1. Training and Feature Extraction**

Open Mal_URL.ipynb.
Run the cells to train a machine learning model and extract features from URLs.
The notebook will output a model saved as url_model.pkl.

**2. Running the GUI**

Open URL_UI.ipynb.
Run the cells to start the Tkinter-based GUI.
Enter a URL in the provided input box and use the buttons to submit the URL, predict its category, and display the result.

**3. GUI Functionality**

Submit: This button captures the URL entered by the user.
Predict: This button processes the URL and predicts its type (benign, defacement, phishing, malware).
Show: This button displays the result in a message box.

### **Model Details**
The model used in this project is a Decision Tree Classifier trained on various features extracted from URLs. The model categorizes URLs into one of four classes:

1. Benign
2. Defacement
3. Phishing
4. Malware
   
### **Future Enhancements**

Adding more sophisticated models like Random Forest or Neural Networks.
Enhancing the GUI with more features, such as batch processing of URLs.

### **Contributing**

Contributions are welcome. Please fork the repository and create a pull request for any changes.

### **License**

This project is licensed under the MIT License.
