# Manual Color Variables Setup for Figma

## Quick Setup Instructions

1. Open your Figma file
2. Go to **Assets** panel (left sidebar)
3. Click **Variables** tab
4. Create a new collection called **"Color System"**
5. Copy each color below one at a time

---

## TEAL (Primary Brand Color)

| Variable Name | Value | Description |
|---|---|---|
| `teal/50` | #f5faf8 | Lightest teal, near-white surfaces |
| `teal/100` | #ecf4f2 | Very light teal, subtle backgrounds |
| `teal/200` | #c7d9d6 | Light teal, borders and dividers |
| `teal/300` | #8ac8c1 | Light-medium teal, secondary accents |
| `teal/400` | #4db6ac | **PRIMARY** - buttons and active states |
| `teal/500` | #4d908b | Button hover states |
| `teal/600` | #4d7d7a | Pressed button states |
| `teal/700` | #4c6a69 | Dark teal-gray, body text |
| `teal/800` | #365655 | Very dark teal, text hover |
| `teal/900` | #1f4141 | Darkest - headings |

---

## GREEN (Success Indicator)

| Variable Name | Value | Description |
|---|---|---|
| `green/50` | #f0fdf4 | Lightest green background |
| `green/100` | #dcfce7 | Very light green background |
| `green/200` | #bbf7d0 | Light green background |
| `green/300` | #86efac | Light-medium green accent |
| `green/400` | #4ade80 | Medium green hover |
| `green/500` | #22c55e | Success color, light variant |
| `green/600` | #16a34a | **PRIMARY** - positive indicators (+12%) |
| `green/700` | #15803d | Dark green hover |
| `green/800` | #166534 | Quality badge label |
| `green/900` | #0b3d1f | Darkest green |

---

## RED (Error Indicator)

| Variable Name | Value | Description |
|---|---|---|
| `red/50` | #fef2f2 | Lightest red background |
| `red/100` | #fee2e2 | Very light red background |
| `red/200` | #fecaca | Light red background |
| `red/300` | #fca5a5 | Light-medium red accent |
| `red/400` | #f87171 | Medium red hover |
| `red/500` | #ef4444 | Error color, medium variant |
| `red/600` | #dc2626 | **PRIMARY** - negative indicators (-0.8%) |
| `red/700` | #b91c1c | Dark red hover |
| `red/800` | #7f1d1d | Very dark red |
| `red/900` | #450a0a | Darkest red |

---

## AMBER (Warning Indicator)

| Variable Name | Value | Description |
|---|---|---|
| `amber/50` | #fffbeb | Lightest amber background |
| `amber/100` | #fef3c7 | Very light amber background |
| `amber/200` | #fde68a | Light amber background |
| `amber/300` | #fcd34d | Light-medium amber accent |
| `amber/400` | #fbbf24 | Medium amber hover |
| `amber/500` | #f59e0b | Warning color, medium variant |
| `amber/600` | #d97706 | Dark amber |
| `amber/700` | #b45309 | **PRIMARY** - Compliance badge & SLA Breach |
| `amber/800` | #92400e | Very dark amber |
| `amber/900` | #5a2e0f | Darkest amber |

---

## PURPLE (Information Accent)

| Variable Name | Value | Description |
|---|---|---|
| `purple/50` | #faf5ff | Lightest purple background |
| `purple/100` | #f3e8ff | Very light purple background |
| `purple/200` | #e9d5ff | Light purple background |
| `purple/300` | #d8b4fe | Light-medium purple accent |
| `purple/400` | #c084fc | Medium purple hover |
| `purple/500` | #a855f7 | Information color, medium variant |
| `purple/600` | #9333ea | Dark purple accent |
| `purple/700` | #7e22ce | Darker purple |
| `purple/800` | #6d28d9 | Very dark purple |
| `purple/900` | #4f46e5 | **PRIMARY** - Experience & CSAT label |

---

## NEUTRAL

| Variable Name | Value | Description |
|---|---|---|
| `white` | #ffffff | Page and card backgrounds |

---

## Step-by-Step Manual Creation

### For Each Color:

1. In **Variables** tab, click **+** button
2. Enter the **Variable Name** (e.g., `teal/50`)
3. Select **Color** type
4. Paste the **Hex Value** (e.g., `#f5faf8`)
5. Click **Create**
6. Repeat for all 51 colors

---

## Organizing with Groups (Optional)

If you want them grouped by family:

1. Create a variable collection called **"Color System"**
2. Create separate groups within it:
   - **Teal** (contains teal/50–900)
   - **Green** (contains green/50–900)
   - **Red** (contains red/50–900)
   - **Amber** (contains amber/50–900)
   - **Purple** (contains purple/50–900)
   - **Neutral** (contains white)

This can be done by naming variables with `/` as separator (e.g., `teal/50` automatically groups under "teal")

---

## Using Variables in Components

Once created, apply to your components:

1. Select a component layer
2. In the **Design** panel, click on a color property (fill, stroke, etc.)
3. Click the **Variables** icon (looks like a slider)
4. Select your color variable (e.g., `teal/400`)
5. Done! The component now uses the variable

---

## Quick Copy-Paste Lists

### All Teal Colors (copy this format)
```
teal/50 → #f5faf8
teal/100 → #ecf4f2
teal/200 → #c7d9d6
teal/300 → #8ac8c1
teal/400 → #4db6ac
teal/500 → #4d908b
teal/600 → #4d7d7a
teal/700 → #4c6a69
teal/800 → #365655
teal/900 → #1f4141
```

### All Green Colors
```
green/50 → #f0fdf4
green/100 → #dcfce7
green/200 → #bbf7d0
green/300 → #86efac
green/400 → #4ade80
green/500 → #22c55e
green/600 → #16a34a
green/700 → #15803d
green/800 → #166534
green/900 → #0b3d1f
```

### All Red Colors
```
red/50 → #fef2f2
red/100 → #fee2e2
red/200 → #fecaca
red/300 → #fca5a5
red/400 → #f87171
red/500 → #ef4444
red/600 → #dc2626
red/700 → #b91c1c
red/800 → #7f1d1d
red/900 → #450a0a
```

### All Amber Colors
```
amber/50 → #fffbeb
amber/100 → #fef3c7
amber/200 → #fde68a
amber/300 → #fcd34d
amber/400 → #fbbf24
amber/500 → #f59e0b
amber/600 → #d97706
amber/700 → #b45309
amber/800 → #92400e
amber/900 → #5a2e0f
```

### All Purple Colors
```
purple/50 → #faf5ff
purple/100 → #f3e8ff
purple/200 → #e9d5ff
purple/300 → #d8b4fe
purple/400 → #c084fc
purple/500 → #a855f7
purple/600 → #9333ea
purple/700 → #7e22ce
purple/800 → #6d28d9
purple/900 → #4f46e5
```

### Neutral
```
white → #ffffff
```

---

## Total: 51 Color Variables

This will take about **10-15 minutes** to create manually, but gives you a complete color system in Figma! ✨
