# Her Fit Self — her fit self ltd

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `herfitselfltd.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/herfitselfltd.mjs`).
> To change the content, edit that file and run `node build.mjs herfitselfltd` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@herfitselfltd.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Per session / $Per block / $Referred) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
Her Fit Self Ltd provides health and fitness support for women in south-east London, working since 2023. We screen and assess before anything else, run supervised training built around what a body can currently tolerate, work with women through pregnancy and after birth with their midwife or GP involved, and give practical everyday nutrition support. Two things we state plainly because the wellness industry generally does not. We do not diagnose or treat anything: we screen, and where something looks clinical we refer you to a doctor rather than train around it. And we use no protected title we do not hold. "Dietitian" and "physiotherapist" are protected by law and restricted to HCPC-registered professionals; "nutritionist" and "personal trainer" are not protected at all, which is worth knowing when you compare practitioners. We promise no weight-loss figure. Site: herfitselfltd.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
