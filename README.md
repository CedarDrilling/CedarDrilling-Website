[README.md](https://github.com/user-attachments/files/26506770/README.md)
# Cedar Drilling – Company Website

Official website for **Cedar Drilling (Pty) Ltd** — an Engineering, Procurement and Construction (EPC) company operating across Central and Southern Africa.

**Live site:** [cedardrilling.com](http://www.cedardrilling.com)

---

## About

Cedar Drilling delivers integrated EPC project solutions across industrial, infrastructure and energy sectors in Central and Southern Africa. Strategic partners include PowerChina, Yellow River Engineering and Sinohydro.

**Registration:** Cedar Drilling (Pty) Ltd — Reg. No. 2019/034153/07

---

## Tech Stack

- Pure HTML / CSS / JavaScript — no frameworks, no dependencies
- Google Fonts (Bebas Neue, DM Sans, DM Mono) loaded via CDN
- Single file: `index.html`

---

## Deployment

### Option 1 — GitHub Pages (this repo)

1. Push `index.html` to the `main` branch
2. Go to **Settings → Pages**
3. Set source to **main branch / root**
4. Site publishes at `https://yourusername.github.io/reponame`

### Option 2 — Netlify

1. Go to [netlify.com/drop](https://netlify.com/drop)
2. Drag and drop `index.html`
3. Live instantly at a `*.netlify.app` URL

### Option 3 — Vercel

1. Import repo at [vercel.com](https://vercel.com)
2. No configuration needed — deploys automatically

---

## Connecting cedardrilling.com

Once deployed, point your domain DNS to your host:

**Netlify / Vercel:** Follow their custom domain guide in the dashboard — both provide step-by-step DNS instructions.

**GitHub Pages:**
1. Add a file named `CNAME` to the repo root containing: `cedardrilling.com`
2. In your domain registrar, set an `A` record pointing to GitHub Pages IPs:
   ```
   185.199.108.153
   185.199.109.153
   185.199.110.153
   185.199.111.153
   ```

---

## Project Structure

```
/
└── index.html        # Full website — all CSS and JS inline
└── README.md         # This file
```

---

## Sections

- **Hero** — Headline, stats (244 MW delivered, 5+ countries, 3 strategic partners)
- **Partners** — PowerChina · Yellow River Engineering · Sinohydro
- **Services** — EPC Delivery, Civil Construction, Energy Infrastructure, Mining Infrastructure, Project Management, Water & Utilities
- **Projects** — Oya Wind Farm (128 MW), Victoria Falls Solar (100 MW), Bunia Hydropower (16 MW), Hwange Underground Coal
- **Geography** — Interactive map: South Africa, Zimbabwe, D.R. Congo, Zambia, Angola, Central Africa
- **Why Cedar** — Integrated EPC, Strong PM Systems, Technical Expertise, Flexible Delivery, Proven in Africa
- **HSE** — Health, Safety & Environment commitments
- **Contact** — Enquiry form + office details

---

## Contact

**Email:** info@cedardrilling.com  
**Tel:** +27 82 779 5959 / +27 79 493 8172  
**Address:** 73 Beyers Naude Dr, Cnr Preller, Johannesburg, Gauteng 2195, South Africa
