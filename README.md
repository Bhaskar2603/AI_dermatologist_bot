# 🧠 AI Dermatologist

A deep learning-powered web application for diagnosing **skin** and **hair diseases**, integrated with intelligent chatbot assistants. This project combines CNN and MobileNet models with a user-friendly interface, allowing users to upload images and receive predictions. Two dedicated chatbots (fine-tuned Mistral-7B LLMs) assist users with personalized advice. Check out: https://bhaskar2603.github.io/AI_dermatologist_bot/

---

## 🚀 Features

- 🔍 Skin disease detection using a custom CNN model
- 💇 Hair disease detection using MobileNet
- 🤖 Chatbot assistants for skin and hair care queries (LLM-based)
- 🔄 Switchable interface between skin and hair chatbots
- 📦 Datasets sourced from Kaggle

---

## 🧠 Technologies Used

- Python, Flask
- TensorFlow, Keras
- MobileNet, Custom CNN
- Mistral 7B LLMs (fine-tuned)
- Gradio (for chatbot interface)
- HTML/CSS/JavaScript (for the web UI)

---

## 📊 Datasets

### ✅ Skin Disease Dataset
- **Source**: [Kaggle – 20 Skin Diseases](https://www.kaggle.com/datasets/haroonalam16/20-skin-diseases-dataset)
- **Classes**:
  - Acne and Rosacea
  - Actinic Keratosis, Basal Cell Carcinoma and other Malignant Lesions
  - Atopic Dermatitis
  - Bullous Disease
  - Cellulitis, Impetigo, and other Bacterial Infections
  - Eczema
  - Exanthems and Drug Eruptions
  - Herpes, HPV, and other STDs
  - Light Diseases and Disorders of Pigmentation
  - Lupus and other Connective Tissue Diseases
  - Melanoma, Nevi, and Moles
  - Poison Ivy and Contact Dermatitis
  - Psoriasis and Lichen Planus
  - Seborrheic Keratoses and Benign Tumors
  - Systemic Disease
  - Tinea, Ringworm, and other Fungal Infections
  - Urticaria (Hives)
  - Vascular Tumors
  - Vasculitis
  - Warts, Molluscum, and other Viral Infections

### ✅ Hair Disease Dataset
- **Source**: [Kaggle – Hair Diseases](https://www.kaggle.com/datasets/sundarannamalai/hair-diseases)
- **Classes**:
  - Alopecia Areata
  - Contact Dermatitis
  - Folliculitis
  - Head Lice
  - Lichen Planus
  - Male Pattern Baldness
  - Psoriasis
  - Seborrheic Dermatitis
  - Telogen Effluvium
  - Tinea Capitis

---

## 📁 Model Notebooks

- 🧴 **Skin Disease Detection (Custom CNN)**: [View Notebook](https://www.kaggle.com/code/bhaskarjyothula/skin-things)
- 💇‍♂️ **Hair Disease Detection (MobileNet)**: [View Notebook](https://www.kaggle.com/code/bhaskarjyothula/mobilenet-hair)

---

## 🧠 Chatbot Interface

Though the disease detection models are not directly integrated with the chatbots, two separate interfaces were built using fine-tuned **Mistral 7B** models to assist users with:

- Skin-related queries
- Hair-related queries

Users can switch between both chatbots on the website and interact naturally.

---

## 📌 Future Work

- Direct integration of detection models with chatbots
- Real-time image upload and capture support
- Deployment of the complete platform
- Enhancing LLM response accuracy and medical reliability

---

## 👨‍💻 Author

**Jyothula Bhaskar**  
B.Tech in Computer Science & Engineering (AI & ML)  
[LinkedIn](https://www.linkedin.com/in/bhaskar-jyothula-974bbb271/) | [Hugging Face](https://huggingface.co/Bhaskar2611) | [GitHub](https://github.com/Bhaskar2603) | [Kaggle](https://www.kaggle.com/bhaskarjyothula)

---

## 📝 License

This project is licensed under the [MIT License](LICENSE).
