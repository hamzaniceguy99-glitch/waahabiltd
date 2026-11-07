# Waahabi — business support services

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `waahabiltd.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/waahabiltd.mjs`).
> To change the content, edit that file and run `node build.mjs waahabiltd` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@waahabiltd.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Quote / $Quote / $Declined) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
Waahabi. Ltd provides business support services from Newport on the Isle of Wight, trading since December 2021: back-office administration, company records and filings, writing down how a business actually runs, and reviewing what it pays for. Business support is an unregulated description, which is exactly why it is worth saying where the edges are, because several of the things clients most often ask a provider like this for are not unregulated at all. Forming companies for clients, supplying a registered office or business address, acting as company secretary or providing a nominee makes a firm a trust or company service provider, which must be registered with HMRC for anti-money-laundering supervision; being on the companies register gives no such permission, and HMRC publishes who is supervised. Giving immigration advice or services in the course of a business is a criminal offence unless you are a qualified person regulated by the Immigration Advice Authority or a lawyer, and that applies even when the help is free and even to filling in a form. Holding clients' money can amount to a payment service needing FCA permission. We do none of those three. Site: waahabiltd.shop
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
