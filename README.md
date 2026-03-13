# brandnewday — Presentation Repo

GitHub Pages site for HTML slide decks built with the **Deep Space** theme.

**Live URL:** https://ericbroadwater.github.io/brandnewday/

---

## What's in this repo

| File | Description |
|------|-------------|
| `astranis.html` | 8-slide Astranis company overview deck |
| `astranis-machineshop.html` | 18-slide Machine Shop Build-Out leadership presentation |
| `Astranis_Machine_Shop_Buildout_Working_Document.md` | Source working document for the machine shop deck |
| `export-to-pptx.py` | Python script — exports `astranis-machineshop.html` content to a `.pptx` file for Google Slides |
| `export-to-pptx.py` → output | `astranis-machineshop.pptx` (gitignored — regenerate locally) |

---

## Viewing presentations

Both HTML decks are live on GitHub Pages:

- https://ericbroadwater.github.io/brandnewday/astranis.html
- https://ericbroadwater.github.io/brandnewday/astranis-machineshop.html

**Navigation:** Arrow keys · Space · scroll · swipe · click nav dots (right edge)

---

## Deep Space Theme

All presentations in this repo use a shared visual system. Reference these values when building new decks.

### Colors
```css
--bg-primary:    #060b14   /* slide background */
--bg-secondary:  #0d1829   /* card backgrounds */
--accent-cyan:   #4fc3f7   /* primary accent, headings, highlights */
--accent-warm:   #e8b86d   /* secondary accent */
--accent-red:    #ef5350   /* danger / warnings */
--accent-green:  #66bb6a   /* success / agree */
--accent-orange: #ffa726   /* caution */
--text-primary:  #f0f4ff   /* main text */
--text-secondary: rgba(200,215,240,0.65)
--text-muted:    rgba(150,175,210,0.4)
--border-subtle: rgba(100,180,255,0.1)
--border-medium: rgba(100,180,255,0.2)
```

### Typography
```
Display / Headings:  Syne (wght 400–800) — Google Fonts
Body text:           IBM Plex Sans (wght 300–500) — Google Fonts
Labels / Mono:       IBM Plex Mono (wght 300–700) — Google Fonts
```

Google Fonts import:
```html
<link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;600;700;800&family=IBM+Plex+Mono:wght@300;400;700&family=IBM+Plex+Sans:wght@300;400;500&display=swap" rel="stylesheet">
```

### Key structural patterns
- **Slide container:** `height: 100vh; height: 100dvh; overflow: hidden; scroll-snap-align: start;`
- **All font sizes:** `clamp(min, preferred, max)` — never fixed px
- **Animations:** `.reveal`, `.reveal-left`, `.reveal-scale` triggered by IntersectionObserver adding `.visible` class
- **Stagger delays:** `.stagger > *:nth-child(n)` with `transition-delay` increments of 0.08s
- **Background elements:** `<canvas id="starCanvas">` (animated star field), `.grid-bg` (subtle dot grid), `.glow-orb` (radial gradient blobs)
- **Navigation:** Progress bar (top), nav dots (right edge), keyboard (arrow keys + space), scroll-snap, touch swipe

---

## Adding a new presentation

1. Copy `astranis-machineshop.html` as a starting template
2. Update the `:root` CSS variables if you want a different accent color (everything else inherits)
3. Replace slide content — keep the `.slide`, `.slide-content`, `.stagger`, `.reveal` structure
4. Update slide counter labels (`01 / N`, `02 / N`, etc.) and total in the JS (`this.slides.length` is automatic)
5. Save to this folder, `git add`, `git commit`, `git push` — GitHub Pages deploys in ~60 seconds

### Commit and push
```bash
cd /Users/ebertmain/Desktop/Stuff/Github/GitHub/brandnewday
git add your-new-deck.html
git commit -m "Add [client/project] presentation"
git push origin main
```

Live at: `https://ericbroadwater.github.io/brandnewday/your-new-deck.html`

---

## Exporting to Google Slides (PPTX)

```bash
# One-time setup
pip3 install python-pptx

# Generate the .pptx
cd /Users/ebertmain/Desktop/Stuff/Github/GitHub/brandnewday
python3 export-to-pptx.py
```

Output: `astranis-machineshop.pptx`

**To open in Google Slides:**
1. Upload the `.pptx` to Google Drive
2. Right-click → Open with → Google Slides
3. All text is editable

> **Font note:** Google Slides will substitute fallback fonts for Syne and IBM Plex Mono unless those fonts are installed on your system. Re-apply manually in Slides if needed for final polish.

To export a **different deck**, copy `export-to-pptx.py`, update the slide content blocks at the bottom of the file, and change the `OUTPUT` filename at the top.

---

## Repo setup notes

- **GitHub Pages:** Enabled on `main` branch, root folder. Settings → Pages → Source: `main / (root)`
- **Remote:** `https://github.com/ericbroadwater/brandnewday.git`
- **Local path:** `/Users/ebertmain/Desktop/Stuff/Github/GitHub/brandnewday/`
- **gitignore:** Blocks `.DS_Store`, `.claude/`, `Desktop/`, `Local Sites/`, WP core files, `*.pptx` output files

---

## Claude context (for future sessions)

When starting a new session to work on this repo, share this README. Key things Claude needs to know:

- This is a **static GitHub Pages repo** — no build tools, no npm, no frameworks
- All presentations are **single self-contained HTML files** with inline CSS and JS
- The `frontend-slides` Claude skill governs how new presentations are structured
- Use the Deep Space theme values above for visual consistency
- The `export-to-pptx.py` script is the canonical way to generate Google Slides-compatible exports
- Git remote is `origin` pointing to `https://github.com/ericbroadwater/brandnewday.git`
