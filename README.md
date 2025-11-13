# 🎓 University of Tehran – LaTeX Presentation Template  
# 🎓 قالب ارائه لاتک دانشگاه تهران

A clean, modern, and customizable LaTeX Beamer template designed for academic presentations at the **University of Tehran**.  
This template is adapted from the SINTEF Beamer theme and customized for my presentation titled:

**Physics-Informed Neural Networks**  
*A Framework for Solving the Two-Stream Instability Problem*

یک قالب حرفه‌ای، مدرن و قابل سفارشی‌سازی برای ارائه‌های دانشگاهی، طراحی شده برای **دانشگاه تهران**.  
این قالب بر اساس تم Beamer سینتف ساخته و برای پرزنتیشن من با عنوان:

**شبکه‌های عصبی آگاه از فیزیک (PINN)**  
*چارچوبی برای حل پدیده ناپایداری دو‌جریانی*  

سفارشی‌سازی شده است.

---

## 🚀 Features  
## 🚀 قابلیت‌ها

- ✔️ Modern & minimal slide design  
- ✔️ Fully compatible with **XeLaTeX**  
- ✔️ Custom beamer class (`sintefbeamer.cls`)  
- ✔️ Customizable color palette (`sintefcolor.sty`)  
- ✔️ Supports animations, TikZ, multicol  
- ✔️ Automatic slide numbering  
- ✔️ Clean academic typography  

- ✔️ طراحی مدرن و مینیمال  
- ✔️ سازگار با کامپایلر **XeLaTeX**  
- ✔️ کلاس بیمر اختصاصی (`sintefbeamer.cls`)  
- ✔️ رنگ‌های قابل سفارشی‌سازی (`sintefcolor.sty`)  
- ✔️ پشتیبانی از انیمیشن، TikZ، چندستونی  
- ✔️ شماره‌گذاری خودکار اسلایدها  
- ✔️ مناسب برای ارائه‌های علمی و دانشگاهی  

---

## 📁 Project Structure  
## 📁 ساختار پروژه

```
UT_Present_Latex_temp/
│
├── main.tex               # Main presentation file / فایل اصلی ارائه
├── customize.tex          # User overrides / تنظیمات و سفارشی‌سازی
├── sintefbeamer.cls       # Custom beamer class / کلاس بیمر
├── beamerthemesintef.sty  # Theme structure / ساختار تم
├── sintefcolor.sty        # Color definitions / رنگ‌ها
├── images/                # Figures & backgrounds / تصاویر و بک‌گراند
└── README.md              # Documentation
```

---

## ▶️ How to Compile  
## ▶️ نحوه کامپایل

### **Using command line**
```bash
xelatex main.tex
```

### **Using VS Code**
Install **LaTeX Workshop** → Press `Ctrl + Alt + B`

### **Using Overleaf**
Just upload the full folder.

---

### **خط فرمان**
```bash
xelatex main.tex
```

### **در VS Code**
پلاگین LaTeX Workshop را نصب کنید → کلید `Ctrl + Alt + B`

### **در Overleaf**
فقط کل پوشه را آپلود کرده و Recompile کنید.

---

## 🎨 Customization  
## 🎨 سفارشی‌سازی

Modify everything in:

```
customize.tex
```

You can change:
- Title / Subtitle  
- Author name  
- Background  
- Color palette  
- Section formatting  

تمام سفارشی‌سازی‌ها در فایل زیر انجام می‌شود:

```
customize.tex
```

موارد قابل تغییر:
- عنوان و زیرعنوان  
- نام ارائه‌دهنده  
- تصویر پس‌زمینه  
- پالت رنگ‌ها  
- قالب‌بندی سکشن‌ها  

---

## 🖼 Adding Images  
## 🖼 افزودن تصویر

```latex
\includegraphics[width=0.8\textwidth]{images/myfigure.png}
```

---

## 🎞 Adding Animations  
## 🎞 افزودن انیمیشن

```latex
\animategraphics[loop, autoplay, width=\linewidth]{15}{images/frame_}{0}{100}
```

---

## 🎯 TikZ Support  
## 🎯 پشتیبانی از TikZ

Libraries loaded:

```latex
\usetikzlibrary{arrows.meta, positioning, calc}
```

کتابخانه‌های TikZ به صورت پیشفرض اضافه شده‌اند.

---

## 📷 Preview (Optional)  
## 📷 پیش‌نمایش (اختیاری)

You may add screenshots here.  
می‌توانید اسکرین‌شات ارائه را اینجا اضافه کنید.

---

## 📝 License  
## 📝 لایسنس

This template is free to use and modify for academic purposes.  
این قالب برای استفاده و ویرایش آزاد است.

---

## 👤 Author  
## 👤 نویسنده

**Hosein Shetaie**  
Master’s Student — Physics  
University of Tehran  

دانشجوی کارشناسی ارشد فیزیک  
دانشگاه تهران  

Feel free to fork, open issues, or contribute!  
در صورت تمایل پروژه را Fork کنید و Pull Request بدهید!

