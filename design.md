# Fitfy Design System

## Color Palette

### Primary Colors
| Color | Hex | Tailwind Class | Usage |
|-------|-----|----------------|-------|
| **Deep Forest Green** | `#0F392B` | `bg-primary` / `text-primary` | Brand identity, primary buttons, headings |
| **Soft Sage** | `#E8F5E9` | `bg-secondary` | Background patterns, secondary elements |
| **Muted Lime** | `#D4E157` | `bg-accent` | Call-to-actions, highlights, icons |

### Neutral Colors
| Color | Hex | Tailwind Class | Usage |
|-------|-----|----------------|-------|
| **Off-White Surface** | `#F9FAFB` | `bg-surface` | Main background, card backgrounds |
| **Dark Gray** | `#1F2937` | `text-gray-900` | Primary text |
| **Medium Gray** | `#4B5563` | `text-gray-600` | Secondary text, descriptions |

## Typography

### Headings
**Font Family:** Playfair Display
**Usage:** Used for main headlines and section titles to convey elegance and authority.
- Tailwind Class: `font-serif`

### Body Text
**Font Family:** Inter
**Usage:** Used for all body copy, UI elements, and buttons for maximum readability.
- Tailwind Class: `font-sans`

## Visual Elements

### Glassmorphism
Used on cards and overlays to create depth and a modern feel.
```css
background: rgba(255, 255, 255, 0.7);
backdrop-filter: blur(12px);
border: 1px solid rgba(255, 255, 255, 0.5);
```

### Shadows
Soft, diffused shadows are used to lift elements off the page.
- `shadow-xl`: For floating elements and hover states.
- `shadow-sm`: For subtle separation.

### Border Radius
- `rounded-3xl`: Used for cards and large containers for a friendly, organic feel.
- `rounded-full`: Used for buttons and badges.
