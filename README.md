# ♿️ توصیف‌گر تصویری برای نابینایان | Image Describer for the Blind

این پروژه یک اپلیکیشن ساده مبتنی بر وب است که از طریق وب‌کم کاربر عکس می‌گیرد، تصویر را تحلیل می‌کند و توضیحی درباره محتوای آن ارائه می‌دهد. سپس این توضیح به‌صورت صوتی پخش می‌شود تا برای کاربران نابینا نیز قابل استفاده باشد.

This project is a simple web-based application that captures a photo using the user's webcam, analyzes the image, and provides a description of its contents. The description is then played as audio, making it accessible for blind users.

---

## 🎯 ویژگی‌ها | Features

- فعال‌سازی دوربین کاربر از طریق مرورگر  
  Activate user's webcam through the browser
- گرفتن عکس با یک کلیک  
  Take a photo with one click
- ارسال عکس به مدل GPT-4o برای تحلیل محتوای تصویر  
  Send image to GPT-4o model for analysis
- دریافت توضیح متنی از OpenAI  
  Receive textual description from OpenAI
- پخش توضیح با استفاده از مدل صوتی OpenAI (TTS)  
  Play description using OpenAI’s TTS model
- طراحی ساده، فارسی و مناسب افراد دارای محدودیت بینایی  
  Simple, Farsi-compatible design suitable for visually impaired users

---

## 🛠️ تکنولوژی‌ها | Technologies

- HTML5 + CSS3
- JavaScript (Vanilla)
- WebRTC (getUserMedia API)
- OpenAI API (Models: GPT-4o and tts-1)

---



## ▶️ اجرای محلی | Run Locally

کلون کردن پروژه | Clone the project

```bash
git clone https://github.com/aminesmkhani/ai-webcam-image-detect.git
```

ورود به دایرکتوری پروژه | Go to the project directory
```bash
cd ai-webcam-image-detect
```

تنظیم کلید API | Set API Key

دریافت کلید ای پی ای  
هشدار : حتما اکانت ای پی ای اتون شارژ داشته باشه

لینک دریافت کلید:https://platform.openai.com/api-keys 



Get Api Key (! Note: Charge API Account Open AI API)

access api key: https://platform.openai.com/api-keys

```bash
const apiKey = "YOUR_OPENAI_API_KEY";
```

اجرای سرور محلی - برای مثال استفاده از افزونه لایو سرور ویژوال استدیو کد

Start and Run the Live Server - etc VS Code

Vs Code - https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer

```bash
http://127.0.0.1:5500/index.html

```

