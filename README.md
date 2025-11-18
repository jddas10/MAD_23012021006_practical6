# Practical 6  

## 🎯 Aim  

Create an Android Application that demonstrates **Frame-by-Frame Animation** and a **Splash Screen using Tween Animation**.

---

## 📖 Description  

This practical demonstrates two major types of animations in Android:

### ✅ 1. Frame-by-Frame Animation  
A sequence of drawable images played one after another (like a flipbook).  
Implemented using:

- **ImageView**
- **AnimationDrawable**
- **<animation-list> drawable**

---

### ✅ 2. Tween Animation (Splash Screen)  
Tween Animation applies transformation effects on a view such as:

- **Scale**
- **Rotate**
- **Translate**
- **Alpha (fade)**  

Implemented using:

- **<set> tag**
- **scale + rotate + translate + alpha**
- **AnimationUtils.loadAnimation()**
- **setAnimationListener()**
- **overridePendingTransition()**

Used in the **SplashActivity** for a smooth intro animation.

---

## 📌 Other Concepts Used  

✔ Immersive Mode  
✔ Display Edge to Edge  
✔ SplashScreen API  
✔ `onWindowFocusChanged()` to start frame animation  
✔ SVG to XML conversion  
✔ anim folder + animation XML  
✔ finish() after splash  
✔ Gradient background using `<shape>` + `<gradient>`

### ⭐ Gradient Requirements  
Splash background uses a **radial gradient** with:  
- centerX = **0.9**  
- centerY = **0.9**  
- radius = **1500**  
- startColor = **Pink**  
- endColor = **Blue**  
- shape = **rectangle**

---

## 📸 Screenshots with Description  

| Screenshot | Description |  
|------------|-------------|  
| <p align="center"/><img src="https://github.com/jddas10/MAD_23012021006_practical6/blob/master/p6_screenshots/Screenshot%202025-11-19%20034018.png" width="250"/> | The **Splash Screen** applies Tween Animation (scale + rotate + translate + alpha) on logo with radial gradient background. |  
| <p align="center"/><img src="https://github.com/jddas10/MAD_23012021006_practical6/blob/master/p6_screenshots/Screenshot%202025-11-19%20034036.png" width="250"/> | The **Main Screen** displays ImageView which plays **Frame-by-Frame animation** using AnimationDrawable. |

---

## 📂 Features Implemented  

### ✔ SplashActivity  
- Tween animation using `<set>`  
- Uses `loadAnimation()`  
- Gradient background  
- Auto-navigation to MainActivity  

### ✔ MainActivity  
- Uses `<animation-list>`  
- Starts animation using `onWindowFocusChanged()`  
- Image plays frame-by-frame animation  

### ✔ Animations Used  
- `<animation-list>`  
- `oneShot="false"`  
- `<set>`  
- `android:startOffset="100"`  
- `android:duration="1000"`  
- `<scale>`  
- `<translate>`  
- `<rotate>`  
- `<alpha>`

---

## 🧪 Result  

The Android application was successfully created to demonstrate **Tween Animation** in Splash Screen and **Frame-by-Frame Animation** in Main Activity.

---

## 📘 Student Details  

> **Name:** *DAVE JAYDATT*  
> **Enrollment:** *23012021006*  
> **Batch:** *5IT-B-1*  
