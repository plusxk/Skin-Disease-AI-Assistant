# Skin Disease AI Assistant

An integrated mobile and backend system for AI-assisted skin disease diagnosis. This project combines a lightweight image classifier and a fine-tuned large language model (LLM), supporting on-device classification and interactive medical Q&A.

## 🩺 Motivation

Diagnosing skin diseases is challenging due to diverse symptoms and appearances. This system is designed for:
- Local image classification on mobile devices
- Protecting user privacy (no cloud uploads)
- Fast diagnostic assistance
- Medical Q&A with a fine-tuned LLM

## 🔧 Features

| Feature            | Description                                             |
|-------------------|---------------------------------------------------------|
| 📱 Mobile Inference | On-device skin disease detection using MobileNetV2     |
| 🧠 LLM Chatbot       | Fine-tuned LLaMA for answering medical questions       |
| 🔐 Privacy-Focused   | No cloud dependency; all inference is offline          |

## 🧠 Models

### Image Classifier
- Backbone: MobileNetV2 (TFLite)
- Trained on mixed dermatology datasets
- Deployed for local mobile inference

### Language Model
- Backbone: LLaMA3 + LoRA (via Unsloth)
- Efficient low-rank fine-tuning
- Config files and tokenizer stored in `lora_model/` (ignored from Git)

## 🗂 Project Structure

