# Website Design System

## 🎨 Kleuren

### Primary
```css
--color-primary: #2563EB;
--color-primary-dark: #1E40AF;
--color-primary-light: #DBEAFE;
```

### Neutrals
```css
--color-black: #111827;
--color-gray-700: #374151;
--color-gray-200: #E5E7EB;
--color-gray-50: #F9FAFB;
--color-white: #FFFFFF;
```

### Statuskleuren
```css
--color-success: #10B981;
--color-warning: #F59E0B;
--color-error: #EF4444;
--color-info: #3B82F6;
```

---

## ✏️ Fonts

### Primair Lettertype
- **Font Family:** Inter
- **Fallback:** sans-serif

### Code Font
- **Font Family:** JetBrains Mono
- **Fallback:** monospace

### Typografieschaal

| Element | Grootte | Gewicht |
|----------|----------|----------|
| H1 | 48px | 700 |
| H2 | 36px | 700 |
| H3 | 30px | 600 |
| H4 | 24px | 600 |
| Body Large | 18px | 400 |
| Body | 16px | 400 |
| Small | 14px | 400 |
| Caption | 12px | 400 |

---

## 📐 Layout

### Container
- Max width: `1280px`
- Desktop padding: `32px`
- Tablet padding: `24px`
- Mobile padding: `16px`

### Grid
- 12 kolommen
- 24px gutter

---

## 🧩 Componenten

### Navbar

**Desktop**
- Sticky navigatie
- Hoogte: 80px
- Logo links
- Menu rechts
- CTA-button rechts

**Mobile**
- Hamburger menu
- Full-screen navigatie overlay

### Hero Section
- Grote headline
- Ondersteunende tekst
- Primaire CTA
- Hero-afbeelding of illustratie

### Buttons

#### Primary Button
- Achtergrond: Primary Blue
- Tekstkleur: Wit
- Border radius: 8px
- Padding: 12px 24px

**Hover**
- Achtergrond: Primary Dark

#### Secondary Button
- Witte achtergrond
- Blauwe border
- Blauwe tekst

### Cards
- Border radius: 12px
- Lichte schaduw
- Padding: 24px

### Formuliervelden
- Hoogte: 48px
- Radius: 8px
- Border: Gray 200

**Focus state**
- Blauwe border
- Subtiele focus shadow

### Footer
- 4 kolommen
- Navigatie-links
- Social links
- Copyright

---

## 📏 Spacing Scale

| Token | Waarde |
|---------|---------|
| xs | 4px |
| sm | 8px |
| md | 16px |
| lg | 24px |
| xl | 32px |
| 2xl | 48px |
| 3xl | 64px |

---

## 🎯 Icons

- Library: Lucide Icons
- Stijl: Outline
- Groottes:
  - 20px
  - 24px

---

## ✨ Animaties

### Standaard
- Duur: 200ms
- Easing: ease-out

### Hover Effect
- Scale: 1.02
- Transition: 200ms

---

## 📱 Responsive Breakpoints

| Device | Breedte |
|----------|----------|
| Mobile | < 640px |
| Tablet | 640px – 1024px |
| Desktop | > 1024px |

---

## ✅ Design Principes

1. Consistente spacing gebruiken.
2. Maximaal één primaire CTA per sectie.
3. Hoge leesbaarheid op mobiel.
4. Toegankelijke kleurcontrasten (WCAG AA).
5. Component-first ontwikkeling.
6. Herbruikbare design tokens voor kleuren, spacing en typografie.