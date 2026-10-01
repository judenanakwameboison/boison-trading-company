# Boison Trading Company

A premium, architectural website for **Boison Trading Company**, a family-run hardware, cement and furniture business in Sekondi, Ghana. It is built with plain HTML, CSS and JavaScript, with heavy parallax and smooth animation that works on every device.

**Live site:** https://judenanakwameboison.github.io/boison-trading-company/

## The problem

A growing hardware, cement and furniture business had no online presence. Customers could not see what was in stock, compare products or ask for prices without visiting the shop.

## The solution

A fast, single-page website that shows the full product range and lets customers request a quote in seconds through WhatsApp or a phone call.

## Features

- **Layered parallax** in the hero, a full-screen parallax break section and a staggered gallery
- **Hardware and cement catalog** with eight product lines
- **Furniture showroom** with a room filter (Living Room, Bedroom, Dining & Kitchen, Office)
- **Request-a-quote form** that opens WhatsApp with the message already written
- **Floating WhatsApp and call buttons** on every screen
- **Gallery and Google Maps location** with a custom dark map style
- **Scroll animations:** text reveals, animated counters, a progress bar, an infinite marquee and 3D card tilt on desktop
- **Fully responsive**, with a full-screen mobile menu and safe-area support for notched phones
- **Accessible:** animations switch off for users who prefer reduced motion

## Design

| Colour | Hex |
|---|---|
| Black | `#090909` |
| Charcoal | `#161616` |
| Dark Bronze | `#6B4A2D` |
| Steel Gray | `#454545` |
| Light Text | `#D6D6D6` |

Typography: Cormorant Garamond (headings) and Manrope (body).

## Built with

- HTML5
- CSS3 (Grid, Flexbox, custom properties, clip-path)
- Vanilla JavaScript (IntersectionObserver, requestAnimationFrame parallax engine)
- Google Fonts and Google Maps embed

No frameworks, no build step, no dependencies.

## Run locally

```bash
git clone https://github.com/judenanakwameboison/boison-trading-company.git
cd boison-trading-company
```

Open `index.html` in your browser.

## Customisation

- **Phone number:** replace `233XXXXXXXXX` in `index.html` (WhatsApp link, call link and the `PHONE` constant in the script). Use the country code with no `+`.
- **Products:** edit the `items` (hardware) and `furn` (furniture) arrays in the script.
- **Images:** replace the files in `img/` using the same file names.

## Author

**Jude Nana Kwame Boison**
Web developer, Ghana
GitHub: [@judenanakwameboison](https://github.com/judenanakwameboison)

## License

Code is released under the MIT License. Images and business branding belong to Boison Trading Company and are not covered by this license.
