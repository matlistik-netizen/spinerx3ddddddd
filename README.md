# SpinerX3D

Prémiový responzívny web pre SpinerX3D — obchod s technológiami, materiálmi a príslušenstvom pre 3D tlač.

## Lokálne spustenie

```bash
pnpm install
pnpm dev
```

Web bude dostupný na `http://localhost:3000`.

## Produkčný statický export

```bash
pnpm build
```

Hotový statický web vznikne v priečinku `out/`.

## Nasadenie na GitHub Pages

1. Vytvorte nový repozitár na GitHube a nahrajte tento projekt do vetvy `main`.
2. V repozitári otvorte **Settings → Pages** a ako zdroj vyberte **GitHub Actions**.
3. Každé odoslanie zmien do `main` automaticky vytvorí a nasadí web.

Workflow automaticky nastaví správnu cestu pre GitHub Pages. Pri použití vlastnej domény stačí z workflow odstrániť premennú `NEXT_PUBLIC_BASE_PATH`.

## Technológie

- Next.js + React + TypeScript
- Tailwind CSS
- Framer Motion
- Lucide ikony
