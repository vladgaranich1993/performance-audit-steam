# Steam Store Performance Audit

**Author:** Vlad Haranich  
**Page audited:** [https://store.steampowered.com/category/racing](https://store.steampowered.com/category/racing)  
**Focus:** Frontend performance audit — asset optimization, render-blocking analysis, and layout stability improvements.

---

## 📊 Summary

This project presents a detailed audit of Steam’s Category Page (Racing), focusing on:

- Unoptimized assets (JPG/PNG/GIF → AVIF/WEBP)
- Large JavaScript bundle (~1.6 MB)
- Render-blocking CSS and fonts
- Main-thread blocking and third-party scripts
- Layout shift (CLS) issues

Each section documents problems, root causes, and proposed solutions with expected Lighthouse score improvements.

---

📄 **Full Report (PDF):**  
👉 [Download or view the Steam Store Performance Audit]([./Performance_Audit_Vlad_Haranich.pdf](https://github.com/vladharanich/steam-performance-audit/raw/main/Performance%20Audit%20Vlad%20Haranich.pdf
))
