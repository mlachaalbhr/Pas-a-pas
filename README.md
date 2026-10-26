# Aula Digital

Plataforma e-learning (MVP) sobre Internet i xarxes. Web estàtica: un sol `index.html`, sense dependències ni build.

## Provar-la en local

```bash
npx serve .
# o bé
python3 -m http.server 3000
```

Obre http://localhost:3000

## Pujar-la a GitHub

```bash
git init
git add .
git commit -m "Primera versió d'Aula Digital"
git branch -M main
git remote add origin https://github.com/EL_TEU_USUARI/aula-digital.git
git push -u origin main
```

## Desplegar a Vercel

1. Entra a vercel.com amb el teu compte de GitHub.
2. **Add New → Project** i tria el repositori `aula-digital`.
3. Framework Preset: **Other**. Deixa Build Command i Output Directory buits.
4. **Deploy**. Rebràs una URL pública `https://aula-digital-xxxx.vercel.app`.
