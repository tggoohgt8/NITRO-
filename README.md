<div align="center">
  <h1>🥷 NINJA-NITRO</h1>
  <p><strong>Discord Nitro Generator & Checker</strong></p>
  <p>
    <img src="https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python">
    <img src="https://img.shields.io/badge/Termux-Compatible-brightgreen?style=for-the-badge&logo=android">
    <img src="https://img.shields.io/badge/License-NINJA%20%E2%84%A2-red?style=for-the-badge">
    <img src="https://img.shields.io/badge/Discord-in7j-7289DA?style=for-the-badge&logo=discord">
  </p>
</div>

---

## 🎯 ما هي الأداة؟

**NINJA-NITRO** هي أداة متخصصة في **توليد وفحص رموز Discord Nitro**، تدعم:
- توليد روابط نيترو (شهر / 3 شهور / سنة)
- فحص صحة الرموز
- إرسال النتائج إلى Webhook
- فحص متعدد الخيوط

---

## 🚀 الميزات

| الميزة | الوصف |
|--------|-------|
| ✅ **توليد رموز** | توليد عشوائي لرموز Nitro |
| ✅ **فحص صحة** | التحقق من صحة الرموز |
| ✅ **Webhook** | إرسال النتائج إلى Discord |
| ✅ **متعدد الخيوط** | فحص سريع بـ 10+ خيوط |
| ✅ **روابط قيفت** | توليد روابط قيفت مباشرة |
| ✅ **حفظ النتائج** | حفظ الرموز الصالحة في ملف |

---

## 📦 التثبيت على Termux

```bash
# تحديث الحزم
pkg update && pkg upgrade -y

# تثبيت الأدوات
pkg install git python python-pip -y

# تحميل الأداة
git clone https://github.com/fearcrazy/Discord-Nitro-Generator.git
cd Discord-Nitro-Generator

# تثبيت المتطلبات
pip install -r requirements.txt

# تشغيل الأداة
python3 main.py
