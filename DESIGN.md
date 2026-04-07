# ON Salon FC LP - Design System

## Brand Identity
- **Brand**: 黄土よもぎ蒸し専門店「ON」
- **Tone**: 温かみ・信頼感・プレミアム感。和のテイストを現代的に。
- **Target**: 30-50代の経営者・副業検討者（男女問わず）

## Color Palette

### Primary - Forest Green（信頼・安定・自然）
- `--primary-900`: #1b4332
- `--primary-700`: #2d6a4f
- `--primary-500`: #40916c
- `--primary-300`: #74c69d
- `--primary-100`: #d8f3dc

### Accent - Warm Gold（高級感・成功）
- `--accent-700`: #bc6c25
- `--accent-500`: #d4a373
- `--accent-300`: #e9c46a
- `--accent-100`: #fefae0

### Neutral
- `--neutral-900`: #1a1a1a
- `--neutral-700`: #404040
- `--neutral-500`: #737373
- `--neutral-300`: #d4d4d4
- `--neutral-100`: #f5f5f5
- `--white`: #ffffff

### Semantic
- `--success`: #06C755 (LINE green, CTA)
- `--danger`: #ef4444

## Typography
- **Font**: Noto Sans JP
- **Hero heading**: 900 weight, 3rem-4.5rem, tight tracking
- **Section heading**: 700 weight, 1.5rem-1.875rem
- **Body**: 400 weight, 0.875rem-1rem, relaxed line-height (1.75)
- **Stat numbers**: 900 weight, 2.5rem-3.5rem

## Spacing
- Section padding: 5rem top/bottom (mobile), 6rem (desktop)
- Content max-width: 720px (narrow/mobile-first)
- Card padding: 1.5rem
- Element gap: 1rem-1.5rem

## Components

### CTA Button
- LINE green (#06C755) for primary action
- Full-width on mobile, max-width 400px
- Pill shape (rounded-full)
- Bold shadow for depth
- Hover: translateY(-2px) + deeper shadow

### Floating CTA
- Fixed bottom, glass morphism background
- Always visible during scroll

### Cards
- rounded-2xl (1rem radius)
- Subtle border + shadow-sm
- White background on colored sections

### Stats
- Large number + small unit text
- Warm cream background (#fefae0)
- 2x2 grid layout

### Comparison Table
- Primary column highlighted with brand green
- Alternating row backgrounds

## Layout Principles
- Mobile-first, single column
- Max-width 720px for readability
- Alternating section backgrounds (white / cream / green / dark green)
- Images with rounded-2xl corners
- Generous whitespace between sections

## Animation (subtle only)
- CTA hover: translateY + shadow transition (0.3s ease)
- FAQ accordion: rotate chevron on open
- No scroll animations (keep it fast and professional)

## Anti-patterns (DO NOT)
- No gradient text
- No Inter font
- No purple/blue color schemes
- No generic tech-startup aesthetics
- No excessive border radius on containers
- No floating decorative blobs or circles
