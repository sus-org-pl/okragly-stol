# Ogólnopolski Okrągły Stół ds. Strategii Młodzieżowej

Strona internetowa wydarzenia **Ogólnopolski Okrągły Stół ds. Strategii Młodzieżowej** — inicjatywy organizowanej przez Stowarzyszenie Umarłych Statutów (SUS) i Fundację PZU, z patronatem honorowym Ministra Edukacji Narodowej.

Wydarzenie odbywa się **25 maja 2026 r. w Warszawie** i stanowi jedno z kluczowych spotkań w procesie konsultacji społecznych nad Krajową Strategią Młodzieżową.

## Stack technologiczny

- **Framework:** [Next.js 16](https://nextjs.org/) (App Router)
- **Język:** TypeScript + React 19
- **Style:** Tailwind CSS v4
- **Ikony:** `react-icons`, `lucide-react`
- **Motywy:** `next-themes` (tryb jasny/ciemny)
- **Hosting:** [Cloudflare Pages](https://pages.cloudflare.com/) via [`@opennextjs/cloudflare`](https://github.com/opennextjs/opennextjs-cloudflare)

## Uruchomienie lokalne

```bash
npm install
npm run dev
```

Aplikacja będzie dostępna pod adresem `https://okraglystol.sus.org.pl`.

## Wdrożenie

Projekt jest wdrażany na Cloudflare Pages. Do budowania i deploymentu służą skrypty:

```bash
npm run deploy    # build + deploy na Cloudflare
npm run preview   # lokalny podgląd środowiska Cloudflare
```

## Struktura projektu

```
app/
├── layout.tsx       # Główny layout, konfiguracja motywów
├── page.tsx         # Strona główna (agenda, rejestracja, partnerzy, kontakt)
└── globals.css      # Globalne style i tokeny

public/              # Assety statyczne (logotypy, grafiki)
```

## Kontakt

- Ogólny: [kontakt@sus.org.pl](mailto:kontakt@sus.org.pl)
- Media: [media@sus.org.pl](mailto:media@sus.org.pl)
