# iFarouq Color Framework Documentation

A comprehensive, modern SASS color framework featuring 100+ color variations, 24 vibrant liquid glass gradients, and extensive utility classes.

<div align="center">

![iFarouqCSS Logo](data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgNDAwIDQwMCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8IS0tIEJhY2tncm91bmQgQ2lyY2xlIHdpdGggR3JhZGllbnQgLS0+CiAgPGRlZnM+CiAgICA8IS0tIE1haW4gR3JhZGllbnQgLS0+CiAgICA8bGluZWFyR3JhZGllbnQgaWQ9Im1haW5HcmFkaWVudCIgeDE9IjAlIiB5MT0iMCUiIHgyPSIxMDAlIiB5Mj0iMTAwJSI+CiAgICAgIDxzdG9wIG9mZnNldD0iMCUiIHN0eWxlPSJzdG9wLWNvbG9yOiM2NjdlZWE7c3RvcC1vcGFjaXR5OjEiIC8+CiAgICAgIDxzdG9wIG9mZnNldD0iNTAlIiBzdHlsZT0ic3RvcC1jb2xvcjojNzY0YmEyO3N0b3Atb3BhY2l0eToxIiAvPgogICAgICA8c3RvcCBvZmZzZXQ9IjEwMCUiIHN0eWxlPSJzdG9wLWNvbG9yOiNmMDkzZmI7c3RvcC1vcGFjaXR5OjEiIC8+CiAgICA8L2xpbmVhckdyYWRpZW50PgogICAgPGxpbmVhckdyYWRpZW50IGlkPSJzZWNvbmRhcnlHcmFkaWVudCIgeDE9IjAlIiB5MT0iMCUiIHgyPSIxMDAlIiB5Mj0iMTAwJSI+CiAgICAgIDxzdG9wIG9mZnNldD0iMCUiIHN0eWxlPSJzdG9wLWNvbG9yOiMwZGNhZjA7c3RvcC1vcGFjaXR5OjEiIC8+CiAgICAgIDxzdG9wIG9mZnNldD0iNTAlIiBzdHlsZT0ic3RvcC1jb2xvcjojMGQ2ZWZkO3N0b3Atb3BhY2l0eToxIiAvPgogICAgICA8c3RvcCBvZmZzZXQ9IjEwMCUiIHN0eWxlPSJzdG9wLWNvbG9yOiM2NjEwZjI7c3RvcC1vcGFjaXR5OjEiIC8+CiAgICA8L2xpbmVhckdyYWRpZW50PgogICAgPGxpbmVhckdyYWRpZW50IGlkPSJhY2NlbnRHcmFkaWVudCIgeDE9IjAlIiB5MT0iMTAwJSIgeDI9IjEwMCUiIHkyPSIwJSI+CiAgICAgIDxzdG9wIG9mZnNldD0iMCUiIHN0eWxlPSJzdG9wLWNvbG9yOiNmZjZiNmI7c3RvcC1vcGFjaXR5OjEiIC8+CiAgICAgIDxzdG9wIG9mZnNldD0iNTAlIiBzdHlsZT0ic3RvcC1jb2xvcjojZmVjYTU3O3N0b3Atb3BhY2l0eToxIiAvPgogICAgICA8c3RvcCBvZmZzZXQ9IjEwMCUiIHN0eWxlPSJzdG9wLWNvbG9yOiNmZjlmZjM7c3RvcC1vcGFjaXR5OjEiIC8+CiAgICA8L2xpbmVhckdyYWRpZW50PgogICAgPGZpbHRlciBpZD0iZ2xhc3MiPgogICAgICA8ZmVHYXVzc2lhbkJsdXIgaW49IlNvdXJjZUdyYXBoaWMiIHN0ZERldmlhdGlvbj0iMiIgcmVzdWx0PSJibHVyIiAvPgogICAgICA8ZmVDb2xvck1hdHJpeCBpbj0iYmx1ciIgbW9kZT0ibWF0cml4IiB2YWx1ZXM9IjEgMCAwIDAgMCAgMCAxIDAgMCAwICAwIDAgMSAwIDAgIDAgMCAwIDE4IC03IiByZXN1bHQ9ImdvbyIgLz4KICAgICAgPGZlQmxlbmQgaW49IlNvdXJjZUdyYXBoaWMiIGluMj0iZ29vIiAvPgogICAgPC9maWx0ZXI+CiAgICA8ZmlsdGVyIGlkPSJzaGFkb3ciIHg9Ii01MCUiIHk9Ii01MCUiIHdpZHRoPSIyMDAlIiBoZWlnaHQ9IjIwMCUiPgogICAgICA8ZmVHYXVzc2lhbkJsdXIgaW49IlNvdXJjZUFscGhhIiBzdGREZXZpYXRpb249IjgiLz4KICAgICAgPGZlT2Zmc2V0IGR4PSIwIiBkeT0iNCIgcmVzdWx0PSJvZmZzZXRibHVyIi8+CiAgICAgIDxmZUNvbXBvbmVudFRyYW5zZmVyPgogICAgICAgIDxmZUZ1bmNBIHR5cGU9ImxpbmVhciIgc2xvcGU9IjAuMyIvPgogICAgICA8L2ZlQ29tcG9uZW50VHJhbnNmZXI+CiAgICAgIDxmZU1lcmdlPgogICAgICAgIDxmZU1lcmdlTm9kZS8+CiAgICAgICAgPGZlTWVyZ2VOb2RlIGluPSJTb3VyY2VHcmFwaGljIi8+CiAgICAgIDwvZmVNZXJnZT4KICAgIDwvZmlsdGVyPgogIDwvZGVmcz4KICA8cmVjdCB3aWR0aD0iNDAwIiBoZWlnaHQ9IjQwMCIgZmlsbD0iI2ZmZmZmZiIgcng9IjIwIi8+CiAgPGNpcmNsZSBjeD0iMzUwIiBjeT0iNTAiIHI9IjgwIiBmaWxsPSJ1cmwoI21haW5HcmFkaWVudCkiIG9wYWNpdHk9IjAuMSIvPgogIDxjaXJjbGUgY3g9IjUwIiBjeT0iMzUwIiByPSIxMDAiIGZpbGw9InVybCgjc2Vjb25kYXJ5R3JhZGllbnQpIiBvcGFjaXR5PSIwLjEiLz4KICA8Y2lyY2xlIGN4PSIzMjAiIGN5PSIzMjAiIHI9IjYwIiBmaWxsPSJ1cmwoI2FjY2VudEdyYWRpZW50KSIgb3BhY2l0eT0iMC4xIi8+CiAgPGcgZmlsdGVyPSJ1cmwoI3NoYWRvdykiPgogICAgPHBhdGggZD0iTSAyMDAgNjAgTCAyODAgMTEwIEwgMjgwIDIxMCBMIDIwMCAyNjAgTCAxMjAgMjEwIEwgMTIwIDExMCBaIiBmaWxsPSJ1cmwoI21haW5HcmFkaWVudCkiIHN0cm9rZT0icmdiYSgyNTUsMjU1LDI1NSwwLjMpIiBzdHJva2Utd2lkdGg9IjMiLz4KICAgIDxwYXRoIGQ9Ik0gMjAwIDYwIEwgMjgwIDExMCBMIDI4MCAyMTAgTCAyMDAgMjYwIEwgMTIwIDIxMCBMIDEyMCAxMTAgWiIgZmlsbD0icmdiYSgyNTUsMjU1LDI1NSwwLjE1KSIgZmlsdGVyPSJ1cmwoI2dsYXNzKSIvPgogICAgPGc+CiAgICAgIDxjaXJjbGUgY3g9IjE4NSIgY3k9IjEyMCIgcj0iMTIiIGZpbGw9IiNmZmZmZmYiLz4KICAgICAgPHJlY3QgeD0iMTc1IiB5PSIxNDUiIHdpZHRoPSIyMCIgaGVpZ2h0PSI3NSIgcng9IjEwIiBmaWxsPSIjZmZmZmZmIi8+CiAgICA8L2c+CiAgICA8Zz4KICAgICAgPHBhdGggZD0iTSAyMTAgMTQ1IEwgMjEwIDIyMCBNIDIxMCAxNDUgTCAyNTAgMTQ1IE0gMjEwIDE4MCBMIDI0MCAxODAiIHN0cm9rZT0iI2ZmZmZmZiIgc3Ryb2tlLXdpZHRoPSIxOCIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiBmaWxsPSJub25lIi8+CiAgICA8L2c+CiAgPC9nPgogIDx0ZXh0IHg9IjIwMCIgeT0iMzEwIiBmb250LWZhbWlseT0iJ0FyaWFsIEJsYWNrJywgJ0FyaWFsIEJvbGQnLCBzYW5zLXNlcmlmIiBmb250LXNpemU9IjM2IiBmb250LXdlaWdodD0iOTAwIiBmaWxsPSJ1cmwoI3NlY29uZGFyeUdyYWRpZW50KSIgdGV4dC1hbmNob3I9Im1pZGRsZSI+aUZhcm91cTwvdGV4dD4KICA8dGV4dCB4PSIyMDAiIHk9IjM0NSIgZm9udC1mYW1pbHk9IidBcmlhbCcsIHNhbnMtc2VyaWYiIGZvbnQtc2l6ZT0iMjgiIGZvbnQtd2VpZ2h0PSJib2xkIiBmaWxsPSJ1cmwoI2FjY2VudEdyYWRpZW50KSIgdGV4dC1hbmNob3I9Im1pZGRsZSIgbGV0dGVyLXNwYWNpbmc9IjMiPkNTUzwvdGV4dD4KICA8dGV4dCB4PSIyMDAiIHk9IjM3MCIgZm9udC1mYW1pbHk9IidBcmlhbCcsIHNhbnMtc2VyaWYiIGZvbnQtc2l6ZT0iMTIiIGZpbGw9IiM2Yzc1N2QiIHRleHQtYW5jaG9yPSJtaWRkbGUiIGxldHRlci1zcGFjaW5nPSIyIj5DT0xPUiBGUkFNRVdPUks8L3RleHQ+CiAgPGcgb3BhY2l0eT0iMC44Ij4KICAgIDxjaXJjbGUgY3g9IjgwIiBjeT0iMjkwIiByPSI1IiBmaWxsPSIjMEQ2RUZEIi8+CiAgICA8Y2lyY2xlIGN4PSI5NSIgY3k9IjI5MCIgcj0iNSIgZmlsbD0iIzY2MTBGMiIvPgogICAgPGNpcmNsZSBjeD0iMTEwIiBjeT0iMjkwIiByPSI1IiBmaWxsPSIjRjYzMzg0Ii8+CiAgICA8Y2lyY2xlIGN4PSIyOTAiIGN5PSIyOTAiIHI9IjUiIGZpbGw9IiMyMEM5OTciLz4KICAgIDxjaXJjbGUgY3g9IjMwNSIgY3k9IjI5MCIgcj0iNSIgZmlsbD0iI0ZGQzEwNyIvPgogICAgPGNpcmNsZSBjeD0iMzIwIiBjeT0iMjkwIiByPSI1IiBmaWxsPSIjREMzNTQ1Ii8+CiAgPC9nPgogIDxlbGxpcHNlIGN4PSIxNjAiIGN5PSIxMDAiIHJ4PSIzMCIgcnk9IjUwIiBmaWxsPSJyZ2JhKDI1NSwyNTUsMjU1LDAuMykiIHRyYW5zZm9ybT0icm90YXRlKC0zMCAxNjAgMTAwKSIvPgo8L3N2Zz4=)

# iFarouqCSS

**A Comprehensive Modern SASS Color Framework**

[![Version](https://img.shields.io/badge/version-2.0.0-blue.svg)](https://github.com/iFarouqDev/iFarouqCSS)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![SASS](https://img.shields.io/badge/SASS-Powered-pink.svg)](https://sass-lang.com/)

**36 Color Families** • **326+ Shades** • **92 Gradients** • **Glassmorphism** • **Hover & Active States**

</div>

---

## 📦 Installation

### Prerequisites
- SASS/SCSS compiler (Dart Sass recommended)
- Node.js (optional, for npm scripts)

### Setup

1. **Download/Clone** the framework files to your project
2. **Place all SCSS files** in a `scss/` directory:
   ```
   scss/
   ├── _variables.scss
   ├── _maps.scss
   ├── _mixins.scss
   ├── _components.scss
   ├── _utilities.scss
   └── colors-framework.scss
   ```

3. **Compile the framework**:
   ```bash
   sass scss/colors-framework.scss dist/iFarouqCSS.css --style=compressed
   ```

4. **Link in your HTML**:
   ```html
   <link rel="stylesheet" href="dist/iFarouqCSS.css">
   ```

---

## 🎨 Color System

### Base Colors
The framework includes 11 color families, each with 9 shade variations (100-900):

- **Blue** - `#0D6EFD`
- **Indigo** - `#6610F2`
- **Purple** - `#6F42C1`
- **Pink** - `#F63384`
- **Red** - `#DC3545`
- **Orange** - `#FD7E14`
- **Yellow** - `#FFC107`
- **Green** - `#198754`
- **Teal** - `#20C997`
- **Cyan** - `#0DCAF0`
- **Gray** - `#ADB5BD`

Plus **Black** (`#000`) and **White** (`#FFF`)

### Color Shades
Each color has 9 shades from lightest (100) to darkest (900):
- `100` - Lightest
- `200` - Very Light
- `300` - Light
- `400` - Medium Light
- `500` - Base (same as color name)
- `600` - Medium Dark
- `700` - Dark
- `800` - Very Dark
- `900` - Darkest

---

## 🌈 Liquid Glass Gradients

24 stunning, vibrant gradients perfect for modern UI design:

| Gradient Name | Description |
|--------------|-------------|
| `aurora-dream` | Purple to pink aurora effect |
| `ocean-bliss` | Cyan to blue to indigo ocean waves |
| `sunset-glory` | Red to yellow to pink sunset |
| `emerald-flow` | Teal to bright green flow |
| `royal-purple` | Deep purple to magenta royalty |
| `cyber-blue` | Electric blue cyberpunk vibes |
| `peachy-paradise` | Peach to pink to purple paradise |
| `mint-breeze` | Mint green refreshing breeze |
| `crimson-tide` | Red to pink crimson wave |
| `golden-hour` | Yellow to orange golden glow |
| `lavender-haze` | Lavender to purple haze |
| `tropical-storm` | Cyan to teal to blue storm |
| `cherry-blossom` | Soft pink cherry blossoms |
| `deep-space` | Dark blue space depths |
| `neon-nights` | Hot pink to orange neon |
| `aqua-marine` | Bright cyan aquatic |
| `fire-opal` | Red to yellow fire |
| `purple-haze` | Purple psychedelic haze |
| `rose-gold` | Rose to gold elegance |
| `electric-lime` | Lime to cyan electric |
| `cosmic-fusion` | Magenta to purple cosmic |
| `tangerine-dream` | Orange tangerine dream |
| `mystic-violet` | Purple to violet mystic |
| `turquoise-wave` | Turquoise wave effect |

---

## 🛠️ Utility Classes

### Text Colors
Apply text colors using the `.text-{color}-{shade}` pattern:

```html
<p class="text-blue-500">Blue text</p>
<p class="text-red-700">Dark red text</p>
<h1 class="text-purple-300">Light purple heading</h1>
```

**Available classes**: `.text-blue`, `.text-blue-100` through `.text-blue-900`, etc.

### Background Colors
Apply background colors using the `.bg-{color}-{shade}` pattern:

```html
<div class="bg-green-500">Green background</div>
<div class="bg-indigo-200">Light indigo background</div>
<section class="bg-gray-800">Dark gray section</section>
```

**Available classes**: `.bg-blue`, `.bg-blue-100` through `.bg-blue-900`, etc.

### Gradient Backgrounds
Apply gradient backgrounds using the `.bg-gradient-{name}` pattern:

```html
<div class="bg-gradient-ocean-bliss">Ocean gradient</div>
<div class="bg-gradient-sunset-glory">Sunset gradient</div>
<header class="bg-gradient-aurora-dream">Aurora header</header>
```

### Gradient Text
Create gradient text effects using `.text-gradient-{name}`:

```html
<h1 class="text-gradient-cyber-blue">Gradient Text</h1>
<p class="text-gradient-fire-opal">Colorful gradient text</p>
```

### Border Colors
Apply border colors using `.border-{color}-{shade}`:

```html
<div class="border-2 border-solid border-blue-500">Blue border</div>
<div class="border-3 border-dashed border-red-600">Dashed red border</div>
```

**Directional borders**:
- `.border-top-{color}-{shade}`
- `.border-right-{color}-{shade}`
- `.border-bottom-{color}-{shade}`
- `.border-left-{color}-{shade}`

### Border Utilities
**Width**: `.border-0`, `.border-1`, `.border-2`, `.border-3`, `.border-4`, `.border-5`

**Style**: `.border-solid`, `.border-dashed`, `.border-dotted`, `.border-double`, `.border-none`

### Gradient Borders
```html
<div class="border-gradient-neon-nights">Gradient border</div>
```

---

## 🪟 Glassmorphism Effects

### Basic Glass Effects

**Standard Glass**:
```html
<div class="glass">
  Frosted glass effect
</div>
```

**Dark Glass**:
```html
<div class="glass-dark">
  Dark frosted glass
</div>
```

**Strong Glass**:
```html
<div class="glass-strong">
  More opaque glass effect
</div>
```

**Subtle Glass**:
```html
<div class="glass-subtle">
  Very light transparent glass
</div>
```

### Liquid Glass with Gradient Tints

The `.liquid-glass-{gradient}` classes create true glassmorphism with a subtle gradient hint:

```html
<div class="liquid-glass-ocean-bliss">
  <h2>Transparent Card</h2>
  <p>Content is visible through the blurred glass</p>
</div>

<div class="liquid-glass-sunset-glory">
  Semi-transparent with sunset tint
</div>
```

**Features**:
- Semi-transparent background (95% see-through)
- 20px blur effect
- Subtle gradient tint at 15% opacity
- Glass-like borders
- Elevated shadows

---

## 🎯 Component Classes

### Buttons

**Solid Buttons**:
```html
<button class="btn-blue-500">Blue Button</button>
<button class="btn-green-600">Green Button</button>
<button class="btn-red-700">Red Button</button>
```

**Outline Buttons**:
```html
<button class="btn-outline-purple-500">Outline Button</button>
<button class="btn-outline-cyan-600">Cyan Outline</button>
```

**Gradient Buttons**:
```html
<button class="btn-gradient-aurora-dream">Gradient Button</button>
<button class="btn-gradient-fire-opal">Fire Button</button>
<button class="btn-gradient-cosmic-fusion">Cosmic Button</button>
```

**Features**: Hover effects, focus states, smooth transitions

### Cards

**Solid Color Cards**:
```html
<div class="card-blue-500">
  <h3>Card Title</h3>
  <p>Card content</p>
</div>
```

**Gradient Cards**:
```html
<div class="card-gradient-ocean-bliss">
  <h3>Ocean Card</h3>
  <p>Beautiful gradient card</p>
</div>
```

**Features**: Hover lift effect, color-matched shadows

### Badges

**Standard Badges**:
```html
<span class="badge-green-500">Success</span>
<span class="badge-red-500">Error</span>
<span class="badge-blue-500">Info</span>
```

**Gradient Badges**:
```html
<span class="badge-gradient-neon-nights">Premium</span>
<span class="badge-gradient-electric-lime">New</span>
```

### Pills

Rounded badge alternatives:
```html
<span class="pill-purple-500">Feature</span>
<span class="pill-teal-600">Active</span>
```

### Alerts

```html
<div class="alert-blue-500">
  <strong>Info!</strong> This is an informational message.
</div>

<div class="alert-red-500">
  <strong>Error!</strong> Something went wrong.
</div>

<div class="alert-green-500">
  <strong>Success!</strong> Operation completed.
</div>
```

**Features**: Left border accent, color-tinted backgrounds

### Progress Bars

**Solid Color Progress**:
```html
<div class="progress-blue-500">
  <div class="progress-bar" style="width: 75%"></div>
</div>
```

**Gradient Progress**:
```html
<div class="progress-gradient-sunset-glory">
  <div class="progress-bar" style="width: 60%"></div>
</div>
```

---

## 💫 Shadow Utilities

### Basic Shadows
```html
<div class="shadow-sm">Small shadow</div>
<div class="shadow">Medium shadow</div>
<div class="shadow-lg">Large shadow</div>
<div class="shadow-none">No shadow</div>
```

### Colored Shadows
Apply color-tinted shadows:
```html
<div class="shadow-blue-500">Blue shadow</div>
<div class="shadow-lg-purple-600">Large purple shadow</div>
<div class="shadow-red-400">Red shadow</div>
```

### Special Shadows
```html
<div class="shadow-gradient">Multi-color gradient shadow</div>
<div class="shadow-glow">Glowing white shadow</div>
```

---

## 🎭 Opacity Utilities

```html
<div class="opacity-0">Invisible (0%)</div>
<div class="opacity-25">25% opacity</div>
<div class="opacity-50">50% opacity</div>
<div class="opacity-75">75% opacity</div>
<div class="opacity-100">100% opacity</div>
```

---

## 📐 CSS Custom Properties

All colors are available as CSS variables:

```css
:root {
  --blue: #0D6EFD;
  --blue-100: #E7F1FF;
  --blue-500: #0D6EFD;
  --blue-900: #031633;
  /* ... and so on */
}
```

**Usage**:
```css
.custom-element {
  background-color: var(--purple-500);
  border-color: var(--purple-700);
  color: var(--white);
}
```

---

## 🎨 SASS Variables & Mixins

### Using Variables in Your SCSS

```scss
@use 'path/to/variables' as *;

.my-component {
  background-color: $blue-500;
  color: $white;
  border: 2px solid $blue-700;
}
```

### Using Color Maps

```scss
@use 'path/to/maps' as *;

@each $name, $color in $colors {
  .custom-#{$name} {
    background: $color;
  }
}
```

### Available Mixins

**Generate Color Utilities**:
```scss
@use 'path/to/mixins' as mix;
@use 'path/to/maps' as *;

@include mix.generate-color-utilities('color', 'my-text', $colors);
```

**Hover State**:
```scss
@use 'path/to/mixins' as mix;

.button {
  @include mix.hover-state(background-color, #0D6EFD);
}
```

**Responsive Breakpoints**:
```scss
@use 'path/to/mixins' as mix;

.responsive-element {
  font-size: 14px;
  
  @include mix.respond-to('medium') {
    font-size: 16px;
  }
  
  @include mix.respond-to('large') {
    font-size: 18px;
  }
}
```

---

## 🌟 Examples & Use Cases

### Modern Landing Page Hero
```html
<section class="bg-gradient-aurora-dream" style="min-height: 100vh; padding: 4rem 2rem;">
  <div class="liquid-glass-cosmic-fusion" style="padding: 3rem; max-width: 800px; margin: 0 auto;">
    <h1 class="text-white" style="font-size: 3rem; margin-bottom: 1rem;">
      Welcome to the Future
    </h1>
    <p class="text-white opacity-75" style="font-size: 1.25rem; margin-bottom: 2rem;">
      Experience cutting-edge design with glassmorphism
    </p>
    <button class="btn-gradient-neon-nights" style="padding: 1rem 2rem; font-size: 1.125rem;">
      Get Started
    </button>
  </div>
</section>
```

### Dashboard Card
```html
<div class="card-gradient-ocean-bliss" style="padding: 2rem; margin: 1rem;">
  <h3 style="margin-bottom: 1rem;">Analytics Overview</h3>
  <div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 1rem;">
    <div class="glass-strong" style="padding: 1.5rem; text-align: center;">
      <h4>Users</h4>
      <p style="font-size: 2rem; font-weight: bold;">1,234</p>
    </div>
    <div class="glass-strong" style="padding: 1.5rem; text-align: center;">
      <h4>Revenue</h4>
      <p style="font-size: 2rem; font-weight: bold;">$45.6K</p>
    </div>
    <div class="glass-strong" style="padding: 1.5rem; text-align: center;">
      <h4>Growth</h4>
      <p style="font-size: 2rem; font-weight: bold;">+23%</p>
    </div>
  </div>
</div>
```

### Pricing Cards
```html
<div style="display: flex; gap: 2rem; padding: 2rem;">
  <div class="liquid-glass-mint-breeze" style="flex: 1; padding: 2rem; text-align: center;">
    <h3>Basic</h3>
    <p class="text-gradient-emerald-flow" style="font-size: 3rem; font-weight: bold;">$9</p>
    <button class="btn-gradient-emerald-flow" style="width: 100%;">Choose Plan</button>
  </div>
  
  <div class="liquid-glass-royal-purple" style="flex: 1; padding: 2rem; text-align: center;">
    <span class="badge-gradient-neon-nights">Popular</span>
    <h3>Pro</h3>
    <p class="text-gradient-royal-purple" style="font-size: 3rem; font-weight: bold;">$29</p>
    <button class="btn-gradient-royal-purple" style="width: 100%;">Choose Plan</button>
  </div>
  
  <div class="liquid-glass-golden-hour" style="flex: 1; padding: 2rem; text-align: center;">
    <h3>Enterprise</h3>
    <p class="text-gradient-golden-hour" style="font-size: 3rem; font-weight: bold;">$99</p>
    <button class="btn-gradient-golden-hour" style="width: 100%;">Choose Plan</button>
  </div>
</div>
```

### Notification Toast
```html
<div class="alert-green-500 shadow-lg" style="position: fixed; top: 20px; right: 20px; max-width: 350px;">
  <div style="display: flex; align-items: center; gap: 1rem;">
    <span class="badge-green-600">✓</span>
    <div>
      <strong>Success!</strong>
      <p>Your changes have been saved.</p>
    </div>
  </div>
</div>
```

---

## 🎯 Best Practices

### 1. **Use Semantic Color Names**
Instead of remembering hex values, use the semantic names:
```html
<!-- Good -->
<button class="btn-blue-500">Primary Action</button>

<!-- Avoid -->
<button style="background: #0D6EFD;">Primary Action</button>
```

### 2. **Maintain Contrast Ratios**
Ensure text is readable on colored backgrounds:
- Light text (100-400) on dark backgrounds (600-900)
- Dark text (600-900) on light backgrounds (100-400)

### 3. **Combine Glass Effects with Gradients**
For stunning modern UIs, layer glass effects over gradient backgrounds:
```html
<div class="bg-gradient-deep-space" style="min-height: 100vh; padding: 2rem;">
  <div class="liquid-glass-cyber-blue" style="padding: 2rem;">
    Content with glassmorphism
  </div>
</div>
```

### 4. **Use Gradients Sparingly**
Gradients are eye-catching—use them for hero sections, CTAs, or featured content.

### 5. **Consistent Spacing**
Combine with spacing utilities from frameworks like Tailwind or Bootstrap for consistent layouts.

---

## 📱 Browser Support

- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Opera (latest)
- ⚠️ IE 11 (limited support, no backdrop-filter)

**Note**: Glassmorphism effects require `backdrop-filter` support. Provide fallbacks for older browsers.

---

## 🚀 Performance Tips

1. **Use compressed CSS** in production (`--style=compressed`)
2. **Include only needed utilities** by customizing the SCSS imports
3. **Optimize gradients** - they're CSS-based, so no image loading needed!
4. **Lazy load** the CSS if not needed above the fold

---

## 📦 File Structure

```
your-project/
├── scss/
│   ├── _variables.scss      # All color variables & shades
│   ├── _maps.scss            # Color maps & gradient definitions
│   ├── _mixins.scss          # Reusable SASS mixins
│   ├── _components.scss      # Styled components
│   ├── _utilities.scss       # Utility classes
│   └── colors-framework.scss # Main entry point
├── dist/
│   └── iFarouqCSS.css       # Compiled CSS
└── index.html                # Your HTML
```

---

## 🤝 Contributing

Want to add more gradients or components? Edit the SCSS files:

**Add a new gradient**:
```scss
// In _maps.scss
$gradients: (
  // ... existing gradients
  "my-custom-gradient": linear-gradient(135deg, #FF0000 0%, #00FF00 100%)
);
```

**Add a new color family**:
```scss
// In _variables.scss
$custom-color: #123456;
$custom-100: #ABCDEF;
// ... add all shades

// In _maps.scss - add to $colors map
```

---

## 📄 License

This framework is free to use for personal and commercial projects.

---

## 🎉 Credits

Created with ❤️ by **iFarouq**

**Special Thanks**: Built with SASS/SCSS and modern CSS features.

---

## 📞 Support

For issues, suggestions, or questions:
- Visit my Portfolio: https://ifarouq.dev
- Open an issue on GitHub: https://github.com/iFarouqDev/iFarouqCSS
- Email: [ifarouq@ifarouq.dev](mailto:ifarouq@ifarouq.dev)
- Twitter: https://x.com/iFarouqDev

---

## 🔮 Roadmap

- [ ] Dark mode color variants
- [ ] Animation utilities
- [ ] More component styles
- [ ] CDN hosting
- [ ] NPM package
- [ ] React/Vue component library

---

**Version**: 1.0.0  
**Last Updated**: December 2025

---

Enjoy building beautiful, modern UIs with the iFarouq Color Framework! 🎨✨
