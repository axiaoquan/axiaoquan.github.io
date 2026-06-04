# Personal Homepage
[My Homepage](https://axiaoquan.github.io/)

A simple static personal homepage, deployed via **GitHub Pages**.

## Layout

```
personal-site/
├── index.html            # All page content lives here — edit this to update your homepage
├── assets/
│   ├── css/              # main.css (template) + academicons.css
│   ├── js/               # main.min.js (mobile nav etc.)
│   └── fonts/            # Font Awesome icon fonts (offline, no CDN required)
├── images/
│   └── avatar.svg        # Replace with your own avatar (jpg/png/svg all OK)
└── README.md
```

## Local preview

```bash
# In this folder, run any static server. Easiest: Python.
cd personal-site
python3 -m http.server 8080
# Then open http://localhost:8080
```

## How to edit

Open `index.html` and replace the placeholder content:

| Section | What to change |
| --- | --- |
| `<title>` | Browser tab title |
| Sidebar `Your Name`, `Tencent | Software Engineer` | Your name and a one-line tagline |
| `mailto:` / `github.com/...` / `LinkedIn` | Your contact links |
| About-me, Work Experience, News, Education, Projects, Skills | Your own content |
| `images/avatar.svg` | Replace with your real photo (recommend a square 400×400 jpg/png) |

## Deploy to GitHub Pages

1. Create a new GitHub repo named **`<your-username>.github.io`** (this exact name → root domain).
2. Push this folder's contents to that repo's `main` branch.
3. In repo Settings → Pages → set Source = `Deploy from a branch`, Branch = `main` / `/(root)`.
4. Wait ~1 minute. Visit `https://<your-username>.github.io`.

## Credit

Template structure adapted from
- [sysu19351118/sysu19351118.github.io](https://github.com/sysu19351118/sysu19351118.github.io)
- which itself was forked from [liujf69/liujf69.github.io](https://github.com/liujf69/liujf69.github.io)

Many thanks to the original authors. The CSS/JS files in `assets/` are inherited from that template.
