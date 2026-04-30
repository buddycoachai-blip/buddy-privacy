# buddy-privacy

Repo che ospita la **privacy policy dell'app Buddy** via GitHub Pages.

## Setup iniziale (una volta)

1. Crea un nuovo repository su GitHub:
   - Vai su https://github.com/new
   - **Repository name**: `buddy-privacy`
   - **Visibility**: Public (necessario per GitHub Pages gratuito)
   - **Initialize**: lascia tutto vuoto (no README, no .gitignore, no license)
   - Click "Create repository"

2. Da terminale (in `C:\Users\aless\buddy-privacy`):
   ```bash
   git init
   git add .
   git commit -m "init: privacy policy v1"
   git branch -M main
   git remote add origin https://github.com/<TUO_USERNAME>/buddy-privacy.git
   git push -u origin main
   ```
   Sostituisci `<TUO_USERNAME>` con il tuo username GitHub.

3. Abilita GitHub Pages:
   - Vai su `https://github.com/<TUO_USERNAME>/buddy-privacy/settings/pages`
   - In **Source**: seleziona `Deploy from a branch`
   - **Branch**: `main`, folder `/ (root)`
   - Click **Save**
   - Attendi 1-2 minuti

4. La privacy sarà online a:
   ```
   https://<TUO_USERNAME>.github.io/buddy-privacy/
   ```

## Aggiornamenti futuri

Modifica `index.md` (e magari aggiorna la data in alto), poi:
```bash
git add index.md
git commit -m "update: privacy policy"
git push
```

GitHub Pages rideploya automaticamente in ~1 minuto.
