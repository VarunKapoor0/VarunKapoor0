# Varun Kapoor

Android & XR engineer. Building at the intersection of spatial computing and AI.

3 years shipping production AR systems at Mercedes-Benz R&D — HoloLens, ARCore, factory floor training systems. USC MS CS '25. Based in LA.

---

## 🕶️ AnimusGlasses — Animus for Meta Ray-Ban Display glasses

> Point your glasses at any object. It identifies it, gives it a personality, and speaks to you in its own voice — **through the glasses speakers.**

Built on the **Meta Wearables Device Access Toolkit (DAT SDK v0.6.0)**. Glasses camera streams I420 YUV frames over Bluetooth → converted to JPEG → Gemini Vision identifies the object and generates a personality → Groq Orpheus TTS speaks the response → audio routed via Bluetooth A2DP back through the glasses speakers. Full pipeline. Working on hardware. Built in one day.

**[→ View source](https://github.com/VarunKapoor0/AnimusGlasses)** &nbsp;·&nbsp; **[→ Download APK](https://varkapoor.com/AnimusGlasses.apk)** &nbsp;·&nbsp; **[→ Setup guide](https://varkapoor.com/projects/animusglasses)**

```
Meta Ray-Ban Display glasses
    ↓ I420 YUV frames over Bluetooth (Meta Wearables DAT SDK)
Android companion app
    ↓ i420ToBitmap() → JPEG → base64
Gemini Vision → object_type, personality, opening_line, voice, vocal_direction
    ↓
Groq Orpheus TTS → WAV → AudioTrack → Bluetooth A2DP → glasses speakers
```

---

## What else I'm building

**[Animus](https://github.com/VarunKapoor0/Animus)** — The web version of the same idea. Point your camera at any object, it gives it a personality and speaks to you in its own voice. Multilingual voice pipeline, WebXR spatial markers, object debate mode. Live at [animusai.app](https://animusai.app)

**[DepthAI](https://github.com/VarunKapoor0/DepthAI)** — Android ARCore app with real-time depth sensing, depth-accurate occlusion rendering, and plane detection using the ARCore Depth API.

---

## Stack

Kotlin · Android · Jetpack Compose · ARCore · Meta Wearables SDK · WebXR · Three.js · React · Gemini API · Groq

---

[varkapoor.com](https://varkapoor.com) &nbsp;·&nbsp; [LinkedIn](https://linkedin.com/in/varkapoor)
