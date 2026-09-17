# Klightten MySQL Themes
## Cinematic Neon Glassmorphism for phpMyAdmin

A hyper-modern, premium 2026-style database dashboard theme for phpMyAdmin running on local LAMPP stacks. Combines Netflix's high-contrast aesthetic with luxury hotel minimalism and glassmorphism UI patterns.

### Design Pillars
- **Cinematic Deep Black** (#080a0f) & **Premium Dark Blue** (#0f172a) backgrounds
- **Electric Neon Blue** (#00f0ff) for primary interactions
- **Striking Neon Orange** (#ff5c00) for warnings & actions
- **Glassmorphism** with backdrop blur effects
- **Luxury Spacing** with generous padding & rounded corners
- **Smooth Animations** with hover scaling & glow effects

### Installation on Local LAMPP

#### Step 1: Locate phpMyAdmin Themes Directory
```bash
cd /opt/lampp/phpmyadmin/themes/
ls -la
```

#### Step 2: Clone or Copy Theme
```bash
# Option A: Clone this repo
git clone https://github.com/Jardeleza0921/Klightten_MYSQL_THEMES.git klightten

# Option B: Download and extract
# Then move to themes directory
mv klightten /opt/lampp/phpmyadmin/themes/
```

#### Step 3: Set Theme in phpMyAdmin
1. Access phpMyAdmin: `http://localhost/phpmyadmin/`
2. Go to **Settings** (bottom left icon)
3. Select **Klightten** from the theme dropdown
4. Save & Refresh

#### Step 4: Clear Browser Cache
```bash
# Hard refresh your browser
Ctrl+Shift+R (Windows/Linux)
Cmd+Shift+R (macOS)
```

### File Structure
```
klightten/
├── theme.json              # Theme metadata & configuration
├── theme.css               # Core theme variables & base styles
├── layout/
│   ├── login.twig         # Redesigned login screen
│   ├── base.twig          # Main layout wrapper
│   └── navigation.twig    # Top navigation with glassmorphism tabs
├── src/
│   ├── buttons.css        # Button component styles (neon glow)
│   ├── cards.css          # Card & database row styles
│   ├── tables.css         # Data grid modernization
│   └── forms.css          # Form input & field styling
├── assets/
│   └── backgrounds/       # Subtle texture overlays
└── img/
    └── logo.svg           # Modern klightten logo
```

### Color Reference
| Element | Color | Hex |
|---------|-------|-----|
| Deep Background | Cinematic Black | `#080a0f` |
| Secondary Background | Premium Blue | `#0f172a` |
| Primary Accent | Neon Blue | `#00f0ff` |
| Warning/Action | Neon Orange | `#ff5c00` |
| Subtle Border | White (20% opacity) | `#ffffff20` |
| Text Primary | Off-White | `#f0f4f8` |
| Text Secondary | Cool Gray | `#8ba3b8` |

### Key Features
✨ **Netflix-Style Database Cards** – Databases display as horizontal movie-like cards with metadata  
🌊 **Glassmorphism Navigation** – Frosted glass tabs with neon underlines  
🎯 **Glow on Hover** – All interactive elements scale smoothly with neon glow  
🔐 **Premium Login Screen** – Sleek authentication experience with gradient accent  
📊 **Modern Data Grids** – Spacious table layouts with hover highlighting  
🎨 **CSS Variables** – Easily customize colors via `:root` definitions  

### Browser Support
- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Requires CSS Grid, Flexbox, and backdrop-filter support

### Customization
Edit the CSS variables in `theme.css` to adjust colors and spacing:
```css
:root {
  --color-bg-primary: #080a0f;
  --color-bg-secondary: #0f172a;
  --color-accent-primary: #00f0ff;
  --color-accent-warning: #ff5c00;
  /* ... etc */
}
```

### License
MIT License – Feel free to use, modify, and distribute!

### Credits
Designed as a premium modernization showcase for legacy database tools.  
Built with ❤️ for students learning that "grandpa tech" can look absolutely stunning in 2026.

---

**Need help?** Check the individual CSS files for detailed comments and customization points.
