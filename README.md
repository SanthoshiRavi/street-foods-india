# 🍛 Street Food of India

> *A culinary journey across 28 states and 8 Union Territories — documenting India's most extraordinary street food culture.*

A collaborative static website built as a **Git workflow teamwork assignment**, celebrating the rich diversity of Indian street food across every region of the country.

---

## 🌐 Live Site

**[View on GitHub Pages →](https://yourusername.github.io/collaborative-static-website/)**

---

## 📸 Pages Overview

| Page | Description |
|------|-------------|
| `index.html` | Home — Hero, filterable food grid (all states), Did You Know facts |
| `about.html` | About — Project story, meet the team, regional diversity guide |
| `contact.html` | Contact — Message form, state selector, community wishlist |
| `style.css` | Full stylesheet — Editorial magazine aesthetic, CSS variables, animations |
| `README.md` | This file — Project documentation |

---

## 👥 Team & Work Split

| Member | File | Branch | Task |
|--------|------|--------|------|
| Member 1 | `index.html` | `feature/home-page` | Home page — Hero, food grid with filter, Did You Know section |
| Member 2 | `about.html` | `feature/about-page` | About page — Story, team section, regional diversity cards |
| Member 3 | `contact.html` | `feature/contact-page` | Contact page — Form with state dropdown, suggest a dish section |
| Member 4 | `style.css` | `feature/stylesheet` | Full design system — Colors, typography, animations, responsive layout |
| Member 5 | `README.md` | `feature/readme` | Project documentation — Setup guide, team table, Git workflow |

---

## 🌿 Git Branching Strategy (Git Flow)

```
main (production — live on GitHub Pages)
  └── develop (integration branch)
        ├── feature/home-page
        ├── feature/about-page
        ├── feature/contact-page
        ├── feature/stylesheet
        └── feature/readme
```

### Step-by-Step Workflow
```bash
# 1. Clone the repository
git clone https://github.com/yourusername/collaborative-static-website.git
cd collaborative-static-website

# 2. Switch to develop branch
git checkout develop

# 3. Create your feature branch (each member does this)
git checkout -b feature/your-page-name

# 4. Work on your file, then stage and commit
git add your-file.html
git commit -m "feat: add home page with food grid and hero section"

# 5. Push your branch
git push origin feature/your-page-name

# 6. Open a Pull Request on GitHub: feature branch → develop
# 7. Team reviews, approves, and merges
# 8. After all features merged into develop: PR from develop → main
# 9. GitHub Pages auto-deploys from main ✅
```

---

## 🎨 Design System

The site uses a **Rich Editorial Magazine** aesthetic — warm, spiced, immersive.

### Color Palette
```css
--ink:       #0f0a05   /* Deep background */
--ember:     #c8460a   /* Primary accent — chilli red-orange */
--saffron:   #e8920a   /* Secondary accent — golden saffron */
--turmeric:  #f5c842   /* Highlight — turmeric yellow */
--cream:     #fdf6e8   /* Background — warm parchment */
--spice:     #8b3a0f   /* Dark spice brown */
```

### Typography
- **Display**: Cormorant Garamond (serif, editorial)
- **Accent**: Bebas Neue (condensed, impactful)
- **Body**: DM Sans (clean, readable)

### Key CSS Classes (for HTML members)
```
.navbar          → sticky top navigation
.hero            → full-height hero section
.section         → base section padding
.section-dark    → dark background section
.section-cream   → cream background section
.food-card       → individual food card
.filter-btn      → region filter button
.btn-primary     → filled CTA button
.btn-secondary   → outlined CTA button
.section-title   → large heading
.section-label   → small uppercase label
.divider-line    → orange accent line
```

---

## 🚀 How to Run Locally

No build tools required — just open in a browser.

```bash
git clone https://github.com/yourusername/collaborative-static-website.git
cd collaborative-static-website

# Open in browser
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux
```

Or use VS Code Live Server extension for hot reload.

---

## 🗺️ States & Foods Covered

| Region | States Covered | Sample Dishes |
|--------|---------------|---------------|
| North | Delhi, UP, Punjab, J&K, Himachal, Uttarakhand | Golgappa, Chole Bhature, Rogan Josh Kulcha, Siddu |
| West | Maharashtra, Gujarat, Rajasthan, Goa | Vada Pav, Pav Bhaji, Dabeli, Fish Recheado, Dal Baati |
| South | Tamil Nadu, Telangana, Kerala, Karnataka, AP | Masala Dosa, Biryani, Kozhikode Halwa, Pesarattu |
| East | West Bengal, Odisha, Bihar, Jharkhand | Kathi Roll, Jhal Muri, Dahibara, Litti Chokha |
| Northeast | Assam, Nagaland, Manipur, Meghalaya, Mizoram, Tripura, Sikkim | Momos, Smoked Pork, Singju, Jadoh |
| Central | Madhya Pradesh, Chhattisgarh | Poha Jalebi, Chila |
| UTs | Puducherry, Chandigarh, Lakshadweep | Creole Curry, Sector 17 Chaat, Tuna Mas Huni |

---

## 🛠️ Tech Stack

- **HTML5** — Semantic structure
- **CSS3** — Custom properties, Flexbox, Grid, animations
- **Vanilla JavaScript** — Filter functionality, form interaction
- **Google Fonts** — Cormorant Garamond, Bebas Neue, DM Sans
- **GitHub Pages** — Static site hosting

---

## 📝 Commit Message Convention

```
feat: add new food card for litti chokha
fix: correct state label on momos card
style: update hero gradient for mobile
docs: update README with team members
```

---

*Built with ❤️ and 🌶️ by Team Street Food India — Git Workflow Assignment*
