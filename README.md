<h1 align="center">🤟🧠 Sign Language FullStack</h1>

<p align="center">
🚀 A Full Stack Deep Learning Application for <b>Sign Language Classification</b><br>
that converts hand gestures into <b>Text 📝</b> and <b>Voice 🔊</b>
</p>

<p align="center">
🧠 Trained on <b>10,000+ samples</b> • 🌐 Django Web Interface • 🔥 PyTorch Model
</p>

---

<h1>🌟 Overview</h1>

This project is designed to **bridge the communication gap** between people who use **sign language 🤟** and those who rely on **spoken or written communication 🗣️📝**.

The system uses **deep learning** to detect and classify hand gestures and convert them into **readable text and voice output**.

✨ The application combines:

• 🤟 Gesture Recognition  
• 🧠 Deep Learning Classification  
• 📝 Text Generation  
• 🔊 Voice Output  
• 🌐 Web Interface  

---

<h1>🎯 Key Objectives</h1>

✅ Recognize sign language gestures using AI  
✅ Convert gestures into meaningful text  
✅ Generate voice output from predicted text  
✅ Provide an easy-to-use web interface  
✅ Demonstrate full-stack AI system integration  

---

<h1>🧠 AI Model Information</h1>

📦 Model File  
```
model/GT.pth
```

📊 Dataset Size  
```
10,000+ training samples
```

🧠 Framework  
```
PyTorch
```

The model is trained to recognize **sign language gestures** and classify them into **textual outputs**.

---

<h1>📂 Project Architecture</h1>

```map
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
```

---

<h1>⚙️ System Components</h1>

📁 <b>base/</b>  
Main Django application containing core logic.

Includes:

• models.py  
• views.py  
• preprocessing pipeline  
• tokenizer logic  

📁 <b>gtking/</b>  
Django project configuration.

Handles:

• server configuration  
• routing  
• application settings  

📁 <b>model/</b>  
Contains the trained **deep learning model** used for classification.

📁 <b>media/</b>  
Stores generated outputs such as:

🔊 voice files  
📝 processed results  

📁 <b>templates/</b>  
Frontend HTML pages used for interaction.

Includes:

• 🏠 index.html – homepage  
• 🤟 tosign.html – text → sign  
• 📝 totext.html – sign → text  

---

<h1>🛠 Technology Stack</h1>

🐍 Python  
🌐 Django  
🔥 PyTorch  
🎨 HTML  
⚡ JavaScript  
🧠 Deep Learning  
📂 JSON Tokenizer  

---

<h1>✨ Features</h1>

🤟 Sign → Text conversion  
📝 Text → Sign visualization  
🔊 Voice generation from text  
🧠 Deep learning gesture classification  
🌐 Web interface for interaction  
📦 Model inference integration  

---

<h1>🚀 Installation & Setup</h1>

1️⃣ Clone the repository

```
git clone https://github.com/Thirumalai-Tech-Developer/Sign_Language_FullStack
```

---

2️⃣ Navigate to project folder

```
cd Sign_Language_FullStack
```

---

3️⃣ Install dependencies

```
pip install -r requirements.txt
```

---

4️⃣ Run database migrations

```
python manage.py migrate
```

---

5️⃣ Start the Django server

```
python manage.py runserver
```

---

6️⃣ Open in browser

```
http://127.0.0.1:8000
```

---

<h1>📊 Application Workflow</h1>

User Gesture 🤟  
⬇  
Preprocessing ⚙️  
⬇  
Deep Learning Model 🧠  
⬇  
Prediction Result 📝  
⬇  
Text Output + Voice Output 🔊  

---

<h1>👨‍💻 Author</h1>

<b>Thirumalai G</b> 🚀  

💻 GitHub  
https://github.com/Thirumalai-Tech-Developer

---

<h1>📜 License</h1>

📚 This project is intended for:

• Educational purposes  
• Research experimentation  
• AI learning demonstrations  

---

<h3 align="center">
⭐ If you like this project, consider giving it a star!
</h3>
