# 📷 Divine Pixels — Photographer App

**Phone లో APK లా Install చేయడానికి ఈ Steps చేయండి:**

---

## ✅ STEP 1 — Firebase Setup (5 నిమిషాలు, ఉచితం)

1. **https://console.firebase.google.com** తెరవండి
2. మీ Gmail **divinepixels.dvn@gmail.com** తో login చేయండి
3. **"Add project"** → Project name: `divine-pixels-dvn` → Continue → Continue → Create project
4. Left menu లో **"Firestore Database"** → **"Create database"** → **"Start in test mode"** → Next → Enable
5. Left menu లో **"Project settings"** (gear icon) → **"Your apps"** → **Web icon `</>`** నొక్కండి
6. App nickname: `divine-pixels-web` → **Register app**
7. **firebaseConfig** లో ఉన్న values copy చేయండి

---

## ✅ STEP 2 — index.html లో Firebase Config పెట్టండి

`index.html` ఫైల్ లో ఈ భాగం కనుగొనండి:
```
const fbCfg = {
  apiKey: "AIzaSyBXXX...",
```

మీరు copy చేసిన values అక్కడ పెట్టండి.

---

## ✅ STEP 3 — GitHub లో Upload (5 నిమిషాలు, ఉచితం)

1. **https://github.com** → Sign up (ఉచితం) లేదా Login
2. **"New repository"** → Name: `divine-pixels` → Public → Create
3. **"uploading an existing file"** link నొక్కండి
4. ఈ files అన్నీ upload చేయండి:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
   - `.github/workflows/deploy.yml`
5. **"Commit changes"** నొక్కండి

---

## ✅ STEP 4 — GitHub Pages Enable

1. Repository → **Settings** → **Pages** (left menu)
2. **Source:** "GitHub Actions" select చేయండి
3. 2-3 నిమిషాలు wait చేయండి
4. మీ App URL వస్తుంది: `https://yourusername.github.io/divine-pixels/`

---

## 📱 STEP 5 — Phone లో Install (APK లా!)

### Android:
1. Chrome browser లో app URL తెరవండి
2. Address bar లో **Install icon** వస్తుంది (లేదా menu → "Add to Home screen")
3. Install చేయండి → Home screen లో icon వస్తుంది

### iPhone:
1. Safari browser లో URL తెరవండి
2. Share button → **"Add to Home Screen"**
3. Add నొక్కండి

---

## 🔄 App Update చేయడం (APK అవసరం లేదు!)

`index.html` లో ఏ మార్పు చేసినా GitHub లో upload చేయండి — **1 నిమిషంలో అందరి phones లో auto-update!**

---

## 📱 Client Booking Link ఇలా పని చేస్తుంది:

```
https://yourusername.github.io/divine-pixels/?mode=clientform&uid=YOUR_ID
```

Client ఈ link తెరిస్తే → Wedding form వస్తుంది → Submit చేస్తే → మీకు notification!

---

**Support:** divinepixels.dvn@gmail.com | 9100308833
