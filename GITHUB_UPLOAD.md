# Návod na nahratie na GitHub

## Krok 1: Vytvorte nový repozitár na GitHub

1. Prejdite na https://github.com/new
2. Zadajte názov repozitára: `glamident-website` (alebo iný názov)
3. Nastavte viditeľnosť: **Public** alebo **Private**
4. **NEVYBERAJTE** žiadne možnosti (README, .gitignore, license) - už ich máme
5. Kliknite na **Create repository**

## Krok 2: Pripojte lokálny repozitár k GitHub

Po vytvorení repozitára GitHub zobrazí inštrukcie. Použite túto sekciu:

**"…or push an existing repository from the command line"**

Skopírujte a spustite tieto príkazy v tomto priečinku:

```bash
git remote add origin https://github.com/VASE_MENO/glamident-website.git
git branch -M main
git push -u origin main
```

**Poznámka:** Nahraďte `VASE_MENO` vaším GitHub používateľským menom.

## Alternatívne: Použite GitHub Desktop

1. Otvorte GitHub Desktop
2. File → Add Local Repository
3. Vyberte tento priečinok
4. Publish repository
5. Zadajte názov a popis
6. Kliknite na Publish

## Overenie

Po nahratí môžete repozitár vidieť na:
`https://github.com/VASE_MENO/glamident-website`

## GitHub Pages (voliteľné)

Ak chcete web hostiť zadarmo na GitHub Pages:

1. Prejdite do Settings repozitára
2. Pages (v ľavom menu)
3. Source: Deploy from a branch
4. Branch: main, folder: / (root)
5. Save

Web bude dostupný na: `https://VASE_MENO.github.io/glamident-website/`
