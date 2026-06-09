---
# Frontend Engineering Skill — ladanjohari.com

## Design System (do not deviate)
Font: Geist (loaded from Google Fonts)
Weights: 400, 500, 600, 700 only

CSS Variables:
  --bg:        #F7F6F3
  --ink:       #111111
  --mid:       #6B6B6B
  --rule:      #D4D3CF
  --hover-row: #F0EFEC
  --accent:    #0066FF
  --accent-dim:#D6E4FF

Max content width: 700px, centered, 28px horizontal padding
Mobile breakpoint: 540px, padding reduces to 20px

Rules:
- No gradients, no shadows (except 1px border rules)
- No dark backgrounds on the page shell — only on ThumbSmall and HoverPreview cards
- Accent #0066FF used only on: italic hero text, hover arrow color, hover states, footer link hover, stack tag hover
- Border weight: 1px solid var(--rule) for all dividers and ThumbSmall border
- Border radius: 5px for ThumbSmall, 10px for HoverPreview, 6px for WorkRow hover, 4px for StackTags
- CursorDot: 8px, #0066FF, RAF lerp at 0.18, mix-blend-mode: multiply
- HoverPreview: 260x174px, appears beside cursor at 28px offset, viewport-clamped
- All transitions: 0.12s-0.2s ease, respect prefers-reduced-motion
---
