# Galaxssia — site oficial

Site static (HTML/CSS/JS, fără build) pentru **galaxssia.com**.
Creative Strategy & Storytelling Studio · Craiova.

## Structură
```
/                 → homepage RO (index.html)
/en/              → homepage EN
/assets/css/      → stiluri
/assets/js/       → scripturi
/assets/img/      → imagini, favicon
robots.txt        → indexare + AI crawlers (GEO)
sitemap.xml       → hartă pentru Google
vercel.json       → config Vercel (preview)
```

## Pipeline de deploy
1. **Local** → scriem/modificăm fișierele aici.
2. **GitHub** → `git push` salvează + versionează.
3. **Vercel** → preview automat la fiecare push (link de test).
4. **FTP → galaxssia.com** → producția reală (serverul prietenului).

## Cum modific ceva
1. Editează fișierul.
2. `git add . && git commit -m "descriere"`
3. `git push` → Vercel actualizează preview-ul automat.
4. Când e ok pe preview → deploy prin FTP pe producție.

## Note
- Fără framework, fără Node → deploy simplu, viteză maximă, SEO bun.
- Credentialele FTP **nu** se pun niciodată în repo (vezi `.gitignore`).
