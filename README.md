# Online-Anomaly-Detection

<h2>Description</h2>
A robust, real-time anomaly detection system that not only identifies unusual patterns in a domestic environment but also pinpoints the exact features causing the anomaly. Developed as a Master's dissertation project, this system combines the power of Deep Learning with an intuitive Graphical User Interface (GUI) for practical, real-world application.


<br />


<h2>Languages and Utilities Used</h2>

- <b>Python 3.7+</b> 
- <b>TensorFlow 2.x</b>
- <b>OpenCV</b>
- <b>Tkinter</b>
- <b>Other libraries: NumPy, Pandas, Matplotlib, Scikit-learn</b>

<h2>Environments Used </h2>

- <b>Windows 11</b> (21H2)
-  <b>Jupyter Notebook</b>
-   <b>Google Collab</b> 

<h2>🚀Projects Highlights</h2>

- **Real-Time Detection:** Processes live camera feeds to identify anomalies instantly
- **Feature Localization:** Uses Grad-CAM to generate heatmaps, visually highlighting the "why" behind an anomaly
- **High Accuracy:** Achieved up to 100% accuracy on specific tasks like toilet lid position and hallway occupancy detection
- **User-Friendly GUI:** Built with Tkinter, allowing for easy model training, testing, and data collection without touching code
- **Domain-Focused:** Tackles practical, real-world problems in home automation and security

<h2>🧠What Problem Does This Solve?</h2>
Anomaly detection is crucial in fields like cybersecurity, healthcare, and industrial monitoring. However, many traditional systems have two key shortcomings: 

<br />


- <b>They struggle with the complexity and speed of real-world data.</b> 
- <b>They act as a "black box," detecting that something is wrong but not what or where.</b>

This project addresses both by creating an interpretable, online detection system for domestic contexts, such as detecting a running tap, an open drawer, or an intruder in a hallway.
<br />


<h2>🛠️ How It Works (The Technical Story)</h2>

The system is built on a powerful integration of a deep learning backend and a responsive frontend. <br />

<h2>🏗️ System Architecture</h2>

**Deep Learning Backend:**
- **Model:** Transfer Learning with a pre-trained VGG16 architecture, fine-tuned for binary classification.
- **Technique:** Uses Grad-CAM for feature localization, producing heatmaps that show the image regions most influential to the model's decision.
- **Training:** Models are trained on custom datasets of ~200 images per class (e.g., "tap on" vs. "tap off").

**Frontend GUI: Built with Tkinter** 

- **Functionality:**
- <b>Live camera feed display and image captureOne-click model training, loading, and saving.</b> 
- <b>Real-time testing on live images or test datasets.</b>
- <b>Integrated data collection tools.</b>















