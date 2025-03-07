### **Speech-to-Image Generation Project**  

#### **📌 Project Overview**  
This project is a **Speech-to-Image Generation** application built using Hugging Face APIs and **Gradio** for an interactive UI. It allows users to **upload an audio file (in Tamil)**, transcribe it, translate the text to English, and then generate an image based on the translated text using AI models.  

#### **🚀 Workflow**  
1. **Speech Recognition (Whisper API - OpenAI Whisper Large V3)**  
   - The app takes an **audio file** as input and converts speech to **Tamil text**.  

2. **Text Translation (Facebook NLLB-200 API)**  
   - The **Tamil text** is then translated into **English** using Facebook’s **NLLB-200 model**.  

3. **Image Generation (Stable Diffusion 2 API - StabilityAI)**  
   - The **translated English text** is used as a prompt to generate an **AI-generated image** using **Stable Diffusion**.  

4. **Display Results**  
   - The app outputs:  
     ✅ **Tamil Transcription**  
     ✅ **English Translation**  
     ✅ **AI-Generated Image**  

#### **🛠 Technologies Used**  
- **Python** (for scripting and API integration)  
- **Gradio** (for UI)  
- **Hugging Face APIs**  
  - OpenAI **Whisper Large V3** (Speech-to-Text)  
  - Facebook **NLLB-200** (Translation)  
  - StabilityAI **Stable Diffusion 2** (Image Generation)  
- **Requests** (for API calls)  
- **Dotenv** (to load API keys securely)  

#### **🔗 Key Features**  
✅ **Fully Automated**: No manual intervention required after uploading an audio file.  
✅ **Tamil to English Translation**: Supports automatic language translation.  
✅ **AI-Generated Images**: Converts transcribed speech into an **AI artwork**.  
✅ **User-Friendly Interface**: Uses Gradio for a simple and interactive UI.  

#### **🔮 Future Enhancements**  
- **Asynchronous API Calls** using `asyncio` for faster performance.  
- **Support for Multiple Languages** beyond Tamil.  
- **Improved Image Prompts** using GPT-based prompt engineering.  
