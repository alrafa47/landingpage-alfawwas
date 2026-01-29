# Al-Fawwaz Catering - Landing Page

Landing page untuk layanan Aqiqah Al-Fawwaz Catering, dibangun dengan [Astro](https://astro.build).

## 🚀 Quick Start

```bash
# Install dependencies
npm install

# Run development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

Buka **http://localhost:4321**

## 📁 Struktur Project

```
src/
├── components/       # Astro components
├── data/            # JSON data files
│   ├── packages.json    # Paket Aqiqah
│   ├── menu.json        # Menu tambahan
│   ├── nasiKotak.json   # Paket Nasi Kotak
│   ├── site.json        # Info kontak & social
│   └── testimonials.json
├── layouts/         # Layout templates
├── pages/           # Route pages
│   ├── index.astro      # Homepage
│   ├── paket.astro      # Halaman Paket
│   └── testimoni.astro  # Halaman Testimoni
└── styles/          # Global CSS

public/
└── images/          # Static assets
```

## 📝 Update Konten

### Paket Aqiqah
Edit `src/data/packages.json`:
```json
{
  "name": "Ekonomi",
  "price": "Rp 2.250.000",
  "features": ["350 Tusuk Sate", "75 Porsi Gule", ...]
}
```

### Kontak & Social Media
Edit `src/data/site.json`:
```json
{
  "whatsapp": "+628155510554",
  "socialLinks": {
    "instagram": "https://instagram.com/...",
    "tiktok": "https://tiktok.com/..."
  }
}
```

### Testimoni
Edit `src/data/testimonials.json`

## 🎨 Color Palette

| Warna | Hex | Penggunaan |
|-------|-----|------------|
| Deep Forest Green | `#2D4636` | Primary |
| Golden Ochre | `#C5A35D` | Accent |
| Off-White | `#F9FBF9` | Background |

## 🔧 Technologies

- [Astro](https://astro.build) - Static Site Generator
- CSS Variables - Styling
- Google Fonts (Plus Jakarta Sans, Playfair Display)
- Google Material Symbols - Icons
