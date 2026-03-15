<h1>*Sign Language FullStack 🤟🧠*</h1>

A Full Stack Deep Learning Application that performs Sign Language Classification and converts sign gestures into Text and Voice.

The system uses a trained deep learning model with 10,000+ training samples and a Django-based backend to serve predictions through a web interface.

--------------------------------------------------

🚀 Project Overview

This project helps improve communication for people using sign language by automatically recognizing hand gestures and converting them into readable text or speech.

The system processes sign inputs, predicts the meaning using a trained model, and outputs the result through a web interface.

Main goals of this project:

• 🤟 Recognize sign language gestures  
• 🧠 Classify gestures using a deep learning model  
• 📝 Convert signs into text  
• 🔊 Generate voice from predicted text  
• 🌐 Provide a simple web interface  

--------------------------------------------------

🧠 Model Information

Model File
model/GT.pth

Dataset Size
10,000+ training samples

The model is trained to recognize sign language gestures and classify them into meaningful outputs.

--------------------------------------------------

📂 Project Structure

Sign_Language_FullStack
│
├── base
│   ├── migrations
│   ├── templates
│   │   ├── index.html
│   │   ├── tosign.html
│   │   └── totext.html
│   │
│   ├── token
│   │   └── tokenizer.json
│   │
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── PreProcess.py
│   └── tokenizer.py
│
├── data
│
├── gtking
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── media
│   └── voice
│
└── model
    └── GT.pth

--------------------------------------------------

⚙️ Main Components

📁 base/
Contains the main Django application including models, views, preprocessing logic, and tokenizer implementation.

📁 gtking/
Django project configuration including settings, routing, and server configuration.

📁 model/
Contains the trained deep learning model used for sign classification.

📁 media/
Stores generated files such as voice outputs.

📁 templates/
Frontend HTML pages used for user interaction.

--------------------------------------------------

🛠 Technologies Used

🐍 Python
🌐 Django
🔥 PyTorch
🎨 HTML
⚡ JavaScript
🧠 Deep Learning

--------------------------------------------------

▶️ How to Run

1️⃣ Clone the repository

git clone https://github.com/Thirumalai-Tech-Developer/Sign_Language_FullStack

2️⃣ Navigate to the project folder

cd Sign_Language_FullStack

3️⃣ Install dependencies

pip install -r requirements.txt

4️⃣ Run database migrations

python manage.py migrate

5️⃣ Start the server

python manage.py runserver

6️⃣ Open in browser

http://127.0.0.1:8000

--------------------------------------------------

✨ Features

🤟 Sign to Text conversion
📝 Text to Sign visualization
🔊 Voice generation from text
🧠 Deep learning gesture classification
🌐 Simple web interface

--------------------------------------------------

👨‍💻 Author

Thirumalai G
GitHub: https://github.com/Thirumalai-Tech-Developer

--------------------------------------------------

📜 License

This project is intended for educational and research purposes.
