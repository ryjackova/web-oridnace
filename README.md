# web-ordinace

Webové stránky ordinace MUDr. Ivany Ryjáčkové

## GitHub Pages + Jekyll

Repozitář je připravený pro GitHub Pages s Jekyllem.

### Co je nastaveno

- `_config.yml` – konfigurace webu
- `index.md` – úvodní stránka
- `kontakt.md` – kontaktní stránka
- `Gemfile` – závislosti pro build (včetně `github-pages`)
- `.github/workflows/jekyll.yml` – automatické nasazení na GitHub Pages

### Zapnutí na GitHubu

1. Otevřete **Settings → Pages**.
2. V části **Build and deployment** zvolte **Source: GitHub Actions**.
3. Po pushi do větve `main` se web automaticky sestaví a publikuje.

### Lokální spuštění (volitelné)

Pro lokální náhled:

1. Nainstalujte Ruby a Bundler.
2. Spusťte:
    - `bundle install`
    - `bundle exec jekyll serve`
3. Otevřete `http://localhost:4000`.
