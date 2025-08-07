# 🚀 دليل رفع البورتفوليو على GitHub

## 📋 ملخص الخطوات

### المرحلة الأولى: إنشاء المستودع على GitHub
1. **اذهب إلى**: [github.com](https://github.com)
2. **اضغط على**: الزر الأخضر "New" أو "+" ← "New repository"
3. **اسم المستودع**: `portfolio` (أو أي اسم تفضله)
4. **مهم جداً**: لا تضع علامة ✓ على "Add a README file"
5. **اضغط**: "Create repository"

---

### المرحلة الثانية: ربط المستودع المحلي بـ GitHub

في Terminal أو Command Prompt، استخدم هذه الأوامر:

```bash
# الانتقال لمجلد المشروع
cd "d:\CV _\portfolio"

# ربط المستودع المحلي بـ GitHub
git remote add origin https://github.com/hanyarafaosman/portfolio.git

# تغيير اسم الفرع الرئيسي إلى main
git branch -M main

# رفع الملفات لـ GitHub
git push -u origin main
```

---

### المرحلة الثالثة: تفعيل GitHub Pages

1. **اذهب إلى**: مستودعك على GitHub
2. **اضغط على**: تبويب "Settings"
3. **انزل إلى**: قسم "Pages" في القائمة الجانبية
4. **في Source**: اختر "Deploy from a branch"
5. **اختر Branch**: "main" و "/ (root)"
6. **اضغط**: "Save"

---

## 🌐 الروابط النهائية

### رابط المستودع:
```
https://github.com/hanyarafaosman/portfolio
```

### رابط الموقع المباشر:
```
https://hanyarafaosman.github.io/portfolio
```

---

## 📱 للمشاركة على وسائل التواصل الاجتماعي

### نموذج منشور LinkedIn:
```
🎯 أسعد بمشاركة بورتفوليو الجديد معكم!

✨ يتضمن خبرتي العملية لأكثر من 15 سنة في:
• تطوير التطبيقات (.NET, Angular)
• إدارة قواعد البيانات (SQL Server, Oracle)
• الذكاء الاصطناعي (Python, Machine Learning)
• DevOps و Cloud Computing

🔗 شاهد البورتفوليو: https://hanyarafaosman.github.io/portfolio

#Portfolio #SoftwareDeveloper #AI #DevOps #TechProfessional
```

### نموذج منشور Facebook/Instagram:
```
🚀 البورتفوليو الجديد جاهز!

15+ سنة خبرة في تطوير التطبيقات والذكاء الاصطناعي 💻

شاهد أعمالي ومشاريعي:
👆 https://hanyarafaosman.github.io/portfolio

#TechProfessional #Portfolio #SoftwareDeveloper
```

---

## ⏱️ الوقت المتوقع
- إنشاء المستودع: **2 دقيقة**
- رفع الملفات: **3 دقائق**
- تفعيل GitHub Pages: **2 دقيقة**
- ظهور الموقع: **5-10 دقائق**

---

## 🆘 في حالة وجود مشاكل

### إذا ظهرت رسالة خطأ عند الـ push:
```bash
git pull origin main --allow-unrelated-histories
git push -u origin main
```

### إذا لم يظهر الموقع:
- تأكد من أن ملف `index.html` موجود
- انتظر 10-15 دقيقة
- تحقق من إعدادات Pages مرة أخرى

---

## 🎉 تهانينا!
بعد اتباع هذه الخطوات، سيكون لديك:
- ✅ مستودع احترافي على GitHub
- ✅ موقع بورتفوليو مباشر ومجاني
- ✅ رابط يمكن مشاركته في السيرة الذاتية
- ✅ إمكانية التحديث في أي وقت

---

*تم إنشاء هذا الدليل بواسطة GitHub Copilot*
