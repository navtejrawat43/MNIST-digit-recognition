# MNIST-digit-recognition
🧠 MNIST Digit Recognition
A simple and interactive digit recognition system using the MNIST dataset. This project features a GUI built with Tkinter, allowing users to draw digits on a canvas and get real-time predictions from a pre-trained neural network.


✨ Features
🔢 Digit Prediction: Recognizes handwritten digits from 0 to 9.

🎨 Interactive GUI: Draw digits directly on the canvas.

🧠 Pre-trained Model: Uses a neural network built with Keras and trained on the MNIST dataset.

⚡ Real-time Inference: Predicts digit immediately after drawing.

🚀 Installation
Follow these steps to get the project up and running:

Clone the repository

bash
Copy
Edit
git clone https://github.com/navtejrawat43/MNIST-digit-recognition.git
cd MNIST-digit-recognition
Install the dependencies

bash
Copy
Edit
pip install -r requirements.txt
Ensure the model file exists

Make sure the mnist.h5 model file is present in the project directory. If it is missing, you can either:

Train your own model (code not included here), or

Download a compatible mnist.h5 model trained on the MNIST dataset.

🎮 Usage
Run the application with:

bash
Copy
Edit
python gui.py
Controls:
✍️ Draw: Use the mouse to draw a digit (0–9) on the canvas.

✅ Recognise: Click the Recognise button to predict the drawn digit.

♻️ Clear: Click Clear to reset the canvas and draw again.

📁 File Structure
bash
Copy
Edit
MNIST-digit-recognition/
│
├── gui.py             # Tkinter-based GUI application
├── mnist.h5           # Pre-trained Keras model for digit classification
├── requirements.txt   # Python dependencies
└── README.md          # Project documentation
📊 Dataset
The model is trained on the MNIST dataset, a collection of 28x28 grayscale images representing handwritten digits (0–9).

📸 Screenshots
(Add actual screenshots if possible)

GUI Window

Example of drawn digit and prediction

🛠️ Future Improvements
🔁 Add support for additional datasets or custom-trained models.

🧩 Improve cross-platform compatibility (currently optimized for Windows with win32gui).

🎨 Enhance GUI design for better user experience and responsiveness.

🔧 Add functionality to re-train model within the app.
