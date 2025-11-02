# 🩺 MediBuddy – Health Monitoring App

A modern Flutter application for **real-time health monitoring** using an **ESP32-based IoT health sensor**. MediBuddy connects via Bluetooth to capture vitals like **Heart Rate (BPM)** and **SpO₂**, providing live data visualization, risk analysis, and a sleek glassmorphism UI.

---

## 📌 Quick notes before you paste

1. **Place the screenshot image files** inside `android/app/src/main/res/` in your repo. The README uses **relative paths**, so the images must be committed to the repository for GitHub to display them.
2. Filenames are **case-sensitive** on many systems and on GitHub. Use the exact names shown below.
3. If images are large (>100 MB) GitHub will reject them — keep them under a few MB each.

---

## 📁 Where to put images (recommended)

Create this folder inside your project repo (run from repo root):

```bash
mkdir -p android/app/src/main/res
# copy your screenshot files into the folder, or put them there from Android Studio
```

Use these exact filenames (or update the README image paths to match your filenames):

```
android/app/src/main/res/Screenshot_1762069032.jpg
android/app/src/main/res/Screenshot_1762069036.jpg
android/app/src/main/res/Screenshot_1762069040.jpg
android/app/src/main/res/Screenshot_1762069072.jpg
android/app/src/main/res/Screenshot_1762069067.jpg
android/app/src/main/res/Screenshot_1762069069.jpg
android/app/src/main/res/Screenshot_1762069085.jpg
android/app/src/main/res/Screenshot_1762069077.jpg
android/app/src/main/res/Screenshot_1762069056.jpg
android/app/src/main/res/image.jpg
```

---

## ✅ How to add images and push to GitHub (step-by-step)

1. Put your image files into `android/app/src/main/res/`.
2. From the repo root run:

```bash
# show files
ls -la android/app/src/main/res/

# stage images
git add android/app/src/main/res/*

# commit
git commit -m "Add MediBuddy screenshots to res folder"

# push to your repo (adjust remote/branch if needed)
git push origin main
```

After push, GitHub will render the images referenced by relative paths in the README.

---

## 📷 README content (single-file — copy & paste)

> Paste the whole content of this file as your `README.md` at the repository root. The image links below reference files expected to be in `android/app/src/main/res/`.

---

# 🩺 MediBuddy – Health Monitoring App

*A modern Flutter application for real-time health monitoring using ESP32 devices with Bluetooth connectivity.*

## 🏥 Features

* **Real-time Health Monitoring**: Live heart rate and SpO₂ monitoring from ESP32 device
* **Bluetooth Connectivity**: Seamless connection to ESP32 health monitoring devices
* **Disease Risk Assessment**: Heart disease risk prediction based on health metrics
* **Beautiful UI**: Modern glassmorphism design with smooth animations

---

## 📁 Screenshots / UI Preview

> Ensure these files exist in `android/app/src/main/res/`

### Splash Screen

![Splash Screen](images/Screenshot_1762069032.jpg)

### Dashboard – Health Metrics

![Dashboard Health Metrics](images/Screenshot_1762069036.jpg)

### Bluetooth Device Connect

![Bluetooth Device Connect](images/Screenshot_1762069040.jpg)

### Risk Factors (Multi-step Form)

![Risk Factors Step](images/Screenshot_1762069072.jpg)

### Personal Info Step

![Personal Info Step](images/Screenshot_1762069067.jpg)

### Health Metrics Step

![Health Metrics Step](images/Screenshot_1762069069.jpg)

### Risk Assessment Result

![Risk Assessment Result](images/Screenshot_1762069085.jpg)

### Review & Predict Step

![Review Your Information](images/Screenshot_1762069077.jpg)

### AI Health Assistant

![AI Health Assistant](images/Screenshot_1762069056.jpg)

### Hardware Setup (ESP32)

![ESP32 Setup](images/image.jpg)

---

## 🛠 Installation

```bash
# clone
git clone https://github.com/omkarMadkar/Helath-Monitor.git
cd Helath-Monitor

# ensure images are inside android/app/src/main/res/
flutter pub get
flutter packages pub run build_runner build
flutter run
```

---

## ⚙️ About image file paths and common reasons images don't show

If images are not showing in the README on GitHub, check these:

1. **Files aren't committed** — make sure you ran `git add` + `git commit` + `git push`.
2. **Wrong path** — markdown image references are relative to the README location. If README is at repo root, `android/app/src/main/res/IMG.jpg` must exist at that path in the repo.
3. **Filename mismatch / case-sensitivity** — `Screenshot.jpg` ≠ `screenshot.jpg` on Linux/GitHub.
4. **Spaces or special characters** — avoid them or URL-encode (use `My%20Image.jpg`).
5. **Using local-only paths** — images on your machine (not in the repo) won't show on GitHub.
6. **Large file size** — GitHub rejects very large files. Use smaller images or Git LFS.
7. **Private repo access** — if someone else views your README in a different repo/branch the images must be present there.

---

## 🔧 Optional: Use an `images/` folder instead (cleaner)

Some people prefer `docs/images/` or `assets/readme_images/`. If you move them, update the markdown paths accordingly.

Example commands to create and move files:

```bash
mkdir -p docs/images
mv android/app/src/main/res/*.jpg docs/images/
# update README image links to docs/images/FILENAME.jpg
```

---

## 🧾 Troubleshooting checklist

1. `git status` — are there uncommitted files?
2. `ls -la android/app/src/main/res/` — do the expected files appear?
3. `git log --name-only -1` — did your last commit include the images?
4. Open the raw file URL `https://raw.githubusercontent.com/<you>/<repo>/main/android/app/src/main/res/Screenshot_1762069032.jpg` — does it load? If yes, README path should work.

---

## 🧭 Final notes

Once you add the images and push, GitHub will render the images in README.md automatically. If you want, I can also generate a smaller, web-optimized copy of each screenshot (reduce width/quality) so they load faster in the README.

---

*Developed with ❤️ by Omkar Madkar — MediBuddy*


