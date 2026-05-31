# 🚀 AppForge AI - Generate Android Apps from Ideas

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Version](https://img.shields.io/badge/Version-1.0.0-blue.svg)
![Status](https://img.shields.io/badge/Status-Active-green.svg)

**AppForge AI** هو منصة ويب احترافية تحول أفكار التطبيقات إلى تطبيقات أندرويد حقيقية باستخدام الذكاء الاصطناعي! 🤖

## 📋 الميزات الرئيسية

✨ **توليد الكود التلقائي**: اكتب فكرتك وسيقوم النظام بتوليد كود Flutter كامل

📱 **بناء APK فوري**: احصل على ملف APK جاهز للتثبيت على الهاتف مباشرة

💬 **محادثة ذكية**: تحسين الفكرة تدريجياً من خلال حوار تفاعلي مع الذكاء الاصطناعي

🎨 **معاينة حية**: اعرض الكود المولد مع إبراز الصيغة قبل البناء

📦 **قوالب جاهزة**: اختر من قوالب احترافية (آلة حاسبة، قائمة مهام، متجر، دردشة)

⚙️ **تخصيص كامل**: اسم الحزمة، الأيقونة، الألوان الأساسية، نوع التنقل

🌐 **دعم لغات متعددة**: واجهة باللغة العربية والإنجليزية

🔒 **أمان عالي**: مصادقة JWT وتشفير كامل

🐳 **Docker Ready**: شغل المشروع كاملاً بسطر واحد

---

## 🛠️ المتطلبات

### قبل البدء، تأكد من تثبيت:

- **Docker & Docker Compose** (نسخة 20.10+)
- **Git** (نسخة 2.30+)

---

## 🚀 التشغيل السريع

### استخدام Docker (الموصى به)

```bash
# استنساخ المستودع
git clone https://github.com/Samyashraf1/appforge-ai.git
cd appforge-ai

# نسخ ملف البيئة
cp .env.example .env

# تشغيل كامل المشروع
docker-compose up -d

# فتح المتصفح
# الواجهة الأمامية: http://localhost:3000
# API Backend: http://localhost:5000
```

---

## ⚙️ متغيرات البيئة

انسخ `.env.example` إلى `.env` وعدّل القيم:

```env
# قاعدة البيانات
DATABASE_URL=postgresql://appforge:secure123@postgres:5432/appforge_db

# مفتاح JWT
JWT_SECRET=your-super-secret-jwt-key-here-min-32-chars

# OpenAI API (اختياري)
OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxxxx

# Anthropic Claude (اختياري)
ANTHROPIC_API_KEY=sk-ant-xxxxxxxxxxxxxxxxxxxxxx
```

---

## 📚 الوثائق

- [Architecture](./docs/ARCHITECTURE.md)
- [API Documentation](./docs/API.md)
- [Contributing Guide](./CONTRIBUTING.md)

---

## 📝 الترخيص

MIT License - شاهد `LICENSE`

---

**النسخة**: 1.0.0  
**الحالة**: 🟢 نشط