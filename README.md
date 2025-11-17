#  Practical-2: Android Activity Life Cycle Demo Application

##  OBJECTIVE
- Display **"Hello World"** in a `TextView` centered on the Activity screen.  
- Customize the layout and `TextView` properties.  
- Demonstrate **all Activity Life Cycle methods** using:
  - `Log`
  - `Toast`
  - `Snackbar`

---

##  APP DESCRIPTION
This Android application demonstrates the **complete Activity Life Cycle** while showing a styled “Hello World” message.

###  The Activity contains:
- A centered `TextView` with:
  - Text: **Hello World**
  - Color: **Holo Blue** (`@android:color/holo_blue_bright`)
  - Size: **27sp**
  - Style: **Bold & Italic**
- Layout background color: **Yellow** (`#FFFF00`)

###  The app displays messages in every Life Cycle method:
- `onCreate()`
- `onStart()`
- `onResume()`
- `onPause()`
- `onStop()`
- `onRestart()`
- `onDestroy()`

Each method shows:
- **Log message** (Logcat)
- **Toast** (top/bottom of screen)
- **Snackbar** (bottom of screen)

This helps visualize the exact flow of an Android Activity’s lifecycle.

---

## 🛠 TECHNOLOGIES USED
- **Android Studio**
- **Kotlin / Java**
- **Android SDK**
- **Material Design Components** (Snackbar)

---

##  USAGE
1. Clone or download the project.  
2. Open the folder in **Android Studio**.  
3. Run the application on:
   - Android Emulator  
   - Physical Device  
4. Observe **Hello World** displayed at the center.  
5. Trigger different Activity states:
   - Rotate screen  
   - Press Home button  
   - Open another Activity  
   - Lock/unlock device  
6. Watch lifecycle logs in:
   - **Logcat**
   - **Toast**
   - **Snackbar**

---

##  OUTPUT

### Screenshot 1  
![Output](https://drive.google.com/uc?export=view&id=1FdplIjLcBuKLeJOCQSZa6GetNPQaqiBM)




---
