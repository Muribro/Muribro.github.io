# Muribro Cars Repair Garage — Image Upload Guide

## Folder Structure

Add the following folders and image files to your GitHub repository:

```
your-repo/
├── logo.png                    ← Your garage logo (already set up)
├── index.html
├── services.html
├── socials.html
├── contact.html
├── style.css
│
├── icons/                      ← Social & UI icons (PNG or JPEG)
│   ├── facebook.png            ← Facebook logo (256x256 recommended)
│   ├── whatsapp.png            ← WhatsApp logo (256x256 recommended)
│   ├── instagram.png           ← Instagram logo (256x256 recommended)
│   ├── phone.png               ← Phone icon (dark version)
│   └── phone-white.png         ← Phone icon (white version for red buttons)
│
├── images/                     ← Service photos (any JPG or PNG)
│   ├── radiator-flushing.jpg
│   ├── car-ac-service.jpg
│   ├── fuel-injector-cleaning.jpg
│   ├── window-tinting.jpg
│   ├── car-polish-detail.jpg
│   ├── smart-paint.jpg
│   ├── oil-filter-change.jpg
│   ├── full-checkup.jpg
│   ├── car-wash.jpg
│   ├── wheel-balancing.jpg
│   └── body-kit.jpg
│
└── partners/                   ← Partner logos (PNG recommended, transparent bg)
    ├── yuasa.png               ← Yuasa Car Battery logo
    ├── boy-ungoy.png
    ├── team-mitsubishi.png
    ├── aspco.png
    └── x1r.png
```

## Notes

- All images use `onerror` fallbacks, so the site still looks clean even if an image hasn't been uploaded yet.
- Service images show a dashed placeholder box until the real photo is added.
- Partner logos show a text fallback until the image is uploaded.
- Recommended service photo size: **800×500px** (landscape).
- Recommended icon size: **256×256px** (square, transparent background).
- Replace all `+971 XX XXX XXXX` placeholders with your real phone numbers.
- Replace all social media URLs with your real profile links.
