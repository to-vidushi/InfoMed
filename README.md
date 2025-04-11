

# 🎙️ InfoMed – AI Healthcare Chatbot for Rural India

## 🧠 Overview

**InfoMed** is an intelligent, multilingual voice-based chatbot designed to **revolutionize rural healthcare** by offering accessible, culturally sensitive, and easy-to-understand medical guidance for **general-purpose illnesses**.  

This AI-powered assistant listens to users speaking in their **local language**, identifies symptoms, and responds with:
- 🩺 **Easily available over-the-counter medicines**
- 🌿 **Safe and trusted home remedies**
- 🗣️ Responses in the **same language and script** the user spoke in (e.g., Hindi input → Response in Devanagari script)

> ⚠️ *Note: InfoMed is not a substitute for professional medical care. Users are advised to consult a doctor for serious or prolonged symptoms.*

---

## 🔍 Features

- **🎤 Voice Input:** Users interact via audio, which is recorded and transcribed in real-time.
- **🌐 Multilingual Support:** Responds in the language spoken by the user.
- **🧪 Symptom Analysis:** Processes user speech to identify common ailments.
- **💊 Medication Suggestion:** Recommends commonly found medicines in rural Indian pharmacies.
- **🏠 Home Remedies:** Offers Ayurvedic and local remedies based on symptoms.
- **📜 Output in Local Script:** For example, Hindi responses are given in **Devanagari**.

---

## 🛠️ Current Status

🚧 **Frontend Development is in Progress**  
We are actively working on building a user-friendly web interface to make InfoMed more accessible and visually engaging for rural users.

---

## 📦 Requirements

Install the following dependencies in a Colab or Python environment:

```bash
!pip install -U -q "google"
!pip install -U -q "google.genai"
!pip install --upgrade "google-cloud-speech"
!pip install SpeechRecognition
!pip install pydub
```

---

## 🚀 How It Works

1. The user speaks their symptoms through the mic.
2. The system records and converts the audio into a `.wav` file.
3. Google’s **Gemini API** processes the audio, interprets the symptoms, and generates a response.
4. Based on the input, it suggests:
   - Over-the-counter medicine
   - A safe and effective home remedy
5. The response is returned in the same language and script used by the user.

---

## 🧪 Example Interaction

**User (in Hindi):**  
"मुझे बुखार है और सिर दर्द हो रहा है।"  

**Chatbot (Response in Devanagari):**  
*आप पेरासिटामोल ले सकते हैं, एक या दो गोली हर 4-6 घंटे पर। घरेलू उपाय के रूप में अदरक की चाय पीना फायदेमंद रहेगा। अगर बुखार कम न हो तो डॉक्टर से मिलें।*

---

## 🤝 Contributing

We welcome ideas, suggestions, and contributions from the open-source community and healthcare professionals. Let’s work together to bring **better healthcare access** to the rural population.

---

## 📌 Note

- **For General Use Only:** Not suitable for emergency or life-threatening conditions.
- **Cultural Sensitivity:** We aim to respect and incorporate traditional knowledge while aligning with modern practices.

---



