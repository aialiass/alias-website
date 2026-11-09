# CLAUDE.md: alias-website

Il sito alias-ai.it: pagine statiche su Vercel. Leggi prima `README.md`.
Ogni push su `main` va in produzione: le modifiche si provano su un branch (Vercel fa l'anteprima).
Repo pubblico: niente dati di clienti, note interne o chiavi.

## L'org aialiass: dove si pusha

| Repo | Cosa | Chi |
|---|---|---|
| `alias-hq` | tutto quello che non è codice: legale, clienti, meeting, brand, pipeline di vendita. Regole complete nel suo `CLAUDE.md` | tutti |
| `alias-filtro` | filtro locale e banco di prova | Gabe |
| `alias-prodotto` | LibreChat modificato, app desktop, server degli studi (`alias/infra/`) | Marco |
| `alias-website` | alias-ai.it su Vercel, `main` = produzione | Ale |

I repo si clonano uno accanto all'altro (`~/Code/alias/`), mai dentro OneDrive o Google Drive.
`git pull` prima di iniziare, commit e push a fine lavoro; il codice passa da un branch e arriva su
`main` quando è provato. Claude non fa push senza la richiesta di chi sta lavorando.
