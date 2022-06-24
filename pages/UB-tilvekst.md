type:: [[prosjekt]]
server:: [[ub-www01]]
status:: [[Behov for videre drift må avklares]]
brukes-av:: "Tilvekstlister i Vortex"
tech:: nginx,php,laravel

- URL: https://ub-tilvekst.uio.no/
- Tjeneste som henter data fra Alma Analytics og lager RSS for tilvekstlister på fagsider, som her: https://www.ub.uio.no/fag/sprak-litteratur/klassisk/nyinnkjop/alle-nye-boker.html
- Status:
	- Hvem bestemmer om denne skal driftes videre?
- Kildekode og dokumentasjon: https://github.com/scriptotek/alma-newbooks-db
- Tech: Nginx+PHP+Laravel 7
- Driftes på ub-www01.uio.no : /srv/ub-tilvekst.uio.no , tilgang: ub-utv
- Data i Postgres på USITs databasehotell
- TODO Sende mail til Kristian og Unni om hva vi gjør videre med denne. Forslag: La den leve videre til den dør naturlig, men gjøre minimalt med drift.