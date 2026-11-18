# Nova — Mobile Voice AI Chatbot (Frontend Only)

A lightweight, realistic mobile-first AI chatbot UI with **zero AI models bundled**.  
Simply paste your **Laptop API URL** (from your laptop running Whisper STT + Qwen2.5 LLM + Kokoro TTS) into the API entry box at the top and start chatting or talking from your phone!

## Features
- Pure static HTML/CSS/JS — deploys to **Vercel** in seconds.
- **API Entry Box** at the top to connect directly to your laptop's backend.
- Full **Text Chat** and **Voice-to-Voice** (`🎙️ Mic -> Laptop Whisper STT -> Laptop Qwen LLM -> Laptop Kokoro TTS -> Mobile Speaker`).
- Automatically saves your Laptop API URL on your mobile device.

## Deploy to Vercel
1. Push this folder (`mobile-chatbot-web`) to a GitHub repository.
2. Go to [vercel.com/new](https://vercel.com/new), import your repository, and click **Deploy** (Framework Preset: **Other**).
3. On your laptop, double-click `E:\own ai model\start_public_api.bat` to get your live HTTPS API URL (`https://xxxx.trycloudflare.com`).
4. Open your Vercel website on your phone, paste the API URL into the box, tap **Connect**, and say **"hi"**!
