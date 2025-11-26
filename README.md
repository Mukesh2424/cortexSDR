# 🎙 CortexSDR – Razorpay Voice SDR Agent

CortexSDR is a voice-based AI Sales Development Representative built for the  
**Murf AI Voice Agent Challenge – Day 5**.

It acts as a Razorpay sales agent that answers FAQs, understands user needs, collects lead details, and generates a structured JSON summary at the end of the call.

---

## 🚀 Features

- 🎤 Voice-first conversation flow
- 💼 Acts as a real Sales Development Representative (SDR)
- 📚 Uses Razorpay FAQ data for accurate responses
- 🧠 Understands customer use-case and business needs
- 📋 Captures lead details:
  - Name
  - Company
  - Email
  - Role
  - Use-case
  - Team size
  - Timeline
- 📄 Outputs structured lead data in JSON
- 🔊 Integrated with **Murf Falcon TTS**
- 🎙 Supports live microphone interaction

---

## 🏦 Company Used

**Razorpay** – Indian Fintech payment gateway company  
Used to answer questions like:
- What does Razorpay do?
- Who is Razorpay for?
- How much do they charge?
- Which payment methods are supported?

---

## 🛠 Tech Stack

- **Google AI Studio**
- **Murf Falcon TTS**
- Web Speech API (Microphone Input)
- JavaScript + HTML
- Python Flask Backend (optional for advanced use)

---

## 🗣 Example Conversation Flow

User:  
> Hi, I’m looking for a payment gateway for my startup.

CortexSDR:  
> Sure! Razorpay helps businesses accept online payments. May I know your name?

User:  
> Mukesh.

CortexSDR:  
> Great, which company do you run?

...  

Finally, agent gives a summary and generates this JSON:

```json
{
  "name": "Mukesh",
  "company": "FalconTech",
  "email": "mukeshfalcon@gmail.com",
  "role": "Founder",
  "use_case": "Subscription payments",
  "team_size": "5",
  "timeline": "Soon"
}
