Responsive Demo — Task 4

What I added
- `index.html` — a small demo page with header/nav, a two-column main area (sidebar + content), large image, and cards.
- `styles.css` — desktop-first styles plus a responsive media query targeting `max-width: 768px`.

Responsive changes applied
- Columns stack vertically on screens ≤ 768px (grid switches to single column).
- Navigation collapses: a visible toggle button shows/hides the nav on narrow screens.
- Large images scale with `width:100%; height:auto;` to avoid overflow.
- Font sizes reduced slightly for mobile; cards stack vertically.
- Overflow-x prevention added to avoid horizontal scrolling.

How to test
1. Open the page in your browser: in PowerShell run:

```powershell
Start-Process "c:\Users\KHAN TEHSEEN\OneDrive\Desktop\TASK-4\index.html"
```

2. In Chrome open DevTools (F12) and toggle the device toolbar (Ctrl+Shift+M). Choose a mobile device (e.g., iPhone 12) or set the viewport width ≤ 768px and verify the layout stacks and the nav toggle works.

Notes / Next steps
- If you want me to apply these changes to your real project HTML/CSS, please paste the HTML/CSS or point me to the file paths and I'll adapt the rules to match your class names and structure.
- I can also add a small CSS transition for the nav, or implement an accessible off-canvas nav if you want a production-ready pattern.