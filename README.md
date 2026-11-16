# Soulful Therapy — Official Practice Website
### Private Psychotherapy Practice of Caroline Vieira, Dip. Couns.
*Clements End, Forest of Dean, Gloucestershire GL16 8LL · Online Across the UK*

---

## 🎨 Brand Design Tokens & Palette

| Token | Hex / Value | Application |
| :--- | :--- | :--- |
| **Primary Teal** | `#007e7c` | Pill CTA buttons, quote accents, badge highlights |
| **Soft Mineral Tint** | `#dee8e9` | Card borders, subtle divider lines, quote box background |
| **Dark Spruce** | `#121c1d` | Exact footer background (`rgb(18, 28, 29)`), statement strips |
| **Footer Border** | `#1e2d2e` | Thin top border dividing main content from the dark footer |
| **Footer Muted Text**| `#8e9293` | Muted subtitle and copyright text in the footer |
| **Backgrounds** | `#ffffff` / `#f7faf9` | Crisp White alternating with Soft Mineral Linen |
| **Headings** | `#121c1d` | Deep Charcoal (`'Lora', serif`, font-weight 600) |
| **Body text** | `#4a5e5d` | Relaxed, readable slate (`'Outfit', sans-serif`, leading 1.7) |

---

## 🧭 Fixed Navigation Bar Architecture
All pages share the exact same fixed navigation bar:
- **No Dropdowns & No Layout Shifts**: Menu items are styled with `font-weight: 500` and `white-space: nowrap` on a single row.
- **Active State**: Active pages are indicated solely via `border-b-2 border-[#007e7c] text-[#007e7c] pb-1` without font weight changes or scaling, preventing any layout shifts.
- **Direct HTML Links**:
  - **Home**: `index.html`
  - **Services**: `counselling-services.html`
  - **About Caroline**: `about-caroline.html`
  - **The Studio**: `the-cabin-studio.html`
  - **Fees & FAQs**: `fees-faqs.html`
  - **Right CTA**: Direct link to `contact.html` with:
    `<a href="contact.html" class="inline-flex items-center justify-center px-5 py-2.5 rounded-full text-sm font-medium bg-[#007e7c] text-white hover:bg-[#006866] transition-colors whitespace-nowrap shadow-sm">Check Availability</a>`

---

## 🌿 Editorial Card Design (Zero Generic AI Icons)
- **"How It Works"**: Uses elegant serif editorial numbers (`01.` / `02.` / `03.`).
- **"Issues & Specialities"**: Clean, high-breathing-room cards with subtle 1px border (`#dee8e9`), Lora serif heading (`text-xl text-[#121c1d]`), and reassuring body copy.
- **Removed Generic Visual Clutter**: All icons-in-boxes and emoji tags have been replaced with quiet, refined typographical layouts.

---

## 🏛️ Exact Footer (Dark Spruce `#121c1d`)
Matching layout and branding:
- Background: `#121c1d` (`rgb(18, 28, 29)`) with border `#1e2d2e`
- Padding: `py-16 px-6`
- Centered layout
- Header-matching logo & brand lockup: Full-color `logo.png` (`h-10 w-auto object-contain`) with accompanying brand text (`CAROLINE VIEIRA` in white / `FOREST OF DEAN` in `#8e9293`) without any color-distorting filters or overlays
- Site title: `Lora` 21px in crisp white (`hover:text-[#dee8e9]`)
- Practice credentials and address in `#8e9293`
- Direct email link with underline: `caroline.vieira108@gmail.com`
- Copyright statement in `#8e9293`

---

## 📐 About Page Spacing Optimization
- Hero section padding adjusted to `pt-10 pb-16 md:pt-14 md:pb-20` directly below the navigation bar.
- Eyebrow badge comfortably positioned 40px–48px below header, eliminating excessive dead space.

---

## 📁 Complete Website Pages
1. [index.html](file:///c:/Users/Ajekiigbe%20Obaloluwa/Desktop/Soulful%20therapy/index.html) — Main Practice Homepage
2. [counselling-services.html](file:///c:/Users/Ajekiigbe%20Obaloluwa/Desktop/Soulful%20therapy/counselling-services.html) — Dedicated Counselling Services Page
3. [about-caroline.html](file:///c:/Users/Ajekiigbe%20Obaloluwa/Desktop/Soulful%20therapy/about-caroline.html) — About Caroline Vieira Deep Dive
4. [the-cabin-studio.html](file:///c:/Users/Ajekiigbe%20Obaloluwa/Desktop/Soulful%20therapy/the-cabin-studio.html) — The Cabin Studio & Location
5. [fees-faqs.html](file:///c:/Users/Ajekiigbe%20Obaloluwa/Desktop/Soulful%20therapy/fees-faqs.html) — Fees & Comprehensive FAQs
6. [contact.html](file:///c:/Users/Ajekiigbe%20Obaloluwa/Desktop/Soulful%20therapy/contact.html) — Dedicated Contact & Availability Page
