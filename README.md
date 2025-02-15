# 🏥 AI-Powered Chest X-Ray Report Generator

🚀 **Automated Radiology Reports with MAIRA-2**  
Harness the power of AI to generate structured radiology reports from chest X-ray images! This project utilizes **MAIRA-2**, a state-of-the-art multimodal AI model, to analyze X-ray images and provide **automatic findings** with just a few clicks. 🩻✨

---

## 📌 Features
✅ **Multimodal AI**: Processes both frontal and lateral chest X-rays.  
✅ **Automated Findings**: Generates structured reports in seconds.  
✅ **User-Friendly Interface**: Built with Gradio for an easy-to-use experience.  
✅ **No Prior Training Required**: Works out-of-the-box with provided image URLs.

---

## ⚡ Quick Start
### 1️⃣ Install Dependencies  
```bash
pip install git+https://github.com/huggingface/transformers.git@88d960937c81a32bfb63356a2e8ecf7999619681 gradio
pip3 install torch torchvision torchaudio
pip install ipywidgets
```

### 2️⃣ Authenticate with Hugging Face  
```python
from huggingface_hub import notebook_login
notebook_login()
```

### 3️⃣ Run the App  
```python
import gradio as gr
demo.launch()
```

---

## 🎯 How It Works
1️⃣ Enter the **frontal** and **lateral** chest X-ray image URLs.  
2️⃣ Add **patient details** like indication, technique, and comparison.  
3️⃣ Click **"Generate Findings"** to let MAIRA-2 analyze and generate a report.  
4️⃣ View the **X-ray images** alongside the **AI-generated findings**.

---

## 🖥️ Gradio Web Interface
An interactive web UI is built with **Gradio**, making it simple to input X-ray images and receive findings in real-time! 🎨🖱️

🔗 **Example Input URLs:**  
- Frontal: [View Image](https://openi.nlm.nih.gov/imgs/512/145/145/CXR145_IM-0290-1001.png)  
- Lateral: [View Image](https://openi.nlm.nih.gov/imgs/512/145/145/CXR145_IM-0290-2001.png)  

---

## 🛠️ Built With
- 🤗 **Transformers** (Hugging Face)  
- 🔥 **PyTorch**  
- 🎨 **Gradio**  

---

## 📜 License
This project is licensed under the **Apache License**. Feel free to use and modify! 🔓

---

## 👩‍💻 Contribute
Have ideas to improve this project? Contributions are welcome! 🤝

⭐ **Star this repo** if you found it helpful! ⭐

