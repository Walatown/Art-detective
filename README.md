# 🎨 Art Detective

**Art Detective** is an AI-powered museum companion app concept that transforms the way visitors interact with art.  
By combining **image recognition**, **storytelling**, and **visual overlays**, the app allows users to scan artworks, uncover hidden details, and engage with art in a more immersive and playful way.

---

## 🧠 Project Overview

- **Type:** University Project  
- **Focus:** UX/UI Design, AI Integration, Museum Experience Innovation  
- **Goal:** To enhance the Rijksmuseum app by integrating **Google Vision API** and **AI-generated insights** for real-time artwork recognition.

Art Detective was designed to show how **AI and design thinking** can enrich cultural exploration — making museums more interactive and accessible.

---

## 💡 Research & Insights

### Competitive Analysis
We began by analyzing existing art recognition apps such as **Google Arts & Culture**, **Smartify**, and **Rijksmuseum**’s own app.  
The key findings revealed opportunities to:

1. Integrate **AI image recognition** for faster artwork information.  
2. Add **personalized recommendations** based on interests.  
3. Introduce **generative filters** and animations to visualize art dynamically.  
4. Combine **education and play** — turning scanning into a learning experience.

📄 [View Competitive Analysis PDF](./assets/art-detective-competitive-analysis.pdf)

---

### “How Might We” Research

We used the **HMW method** to define problem statements and opportunities:

- **HMW make our app different from existing art recognition apps?**  
  → By adding gamified interactions (scavenger hunts, quizzes, and face-swaps).

- **HMW build a fast and accurate image recognition tool?**  
  → By integrating **Google Vision API** with **Rijksmuseum’s open API**.

- **HMW keep users curious after scanning?**  
  → Through fun facts, animations, and dynamic overlays.

- **HMW protect user privacy?**  
  → Real-time scans only; no cloud storage or user data retention.

---

## 📱 App Flow

The app’s journey focuses on **simplicity and delight**:

1. **Welcome Screen** → Introduction or login.  
2. **Scanning Screen** → Point the camera at an artwork.  
3. **Result View** → Artwork details, fun facts, and animation overlays.

Each step was designed to maintain the visitor’s focus on the artwork, not the interface.


## 🤖 Integrations

### Google Vision API
Used for identifying artworks through image recognition.  
Provides labels, color palettes, and object detection with minimal setup.

### Rijksmuseum API
Provides artwork metadata — artist name, creation year, and descriptions.

### Privacy Considerations
- No user data is stored.
- Images are analyzed in real-time and immediately deleted.
- Scanning focuses only on artwork (context-aware detection planned).

🧩 Stack:
- Swift (iOS)
- Google Vision API
- Rijksmuseum API
- Adobe After Effects (animation overlays)
- Figma (UI/UX design)


## 🧾 License

This project is part of an academic portfolio and is provided for educational purposes only.  
All media and code are © 2025 the respective creators. Use for demonstration and learning only.

---

### 🌐 Links

- [Rijksmuseum API Docs](https://data.rijksmuseum.nl/object-metadata/api/)
- [Google Vision API](https://cloud.google.com/vision)

---
