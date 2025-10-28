# Steam Store Performance Audit

**Author:** Vlad Haranich  
**Page audited:** [https://store.steampowered.com/category/racing](https://web.archive.org/web/20251027102626/https://store.steampowered.com/category/racing)  (**Download mht** file to get the audited version)   
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
👉 [Download or view the Steam Store Performance Audit](https://github.com/vladgaranich1993/performance-audit-steam/blob/main/Performance%20Audit%20Vlad%20Haranich.pdf)
