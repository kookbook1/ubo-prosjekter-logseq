type:: [[system]]
server:: [[ub-www01]]
status:: [[Må avklares]]
brukes-av:: "Tilvekstlister i Vortex"
tech:: nginx,php,laravel

- [[Sammendrag]]: Tjeneste som henter data fra Alma Analytics og lager RSS for tilvekstlister på fagsider, som her: https://www.ub.uio.no/fag/sprak-litteratur/klassisk/nyinnkjop/alle-nye-boker.html
- [[URL]]: https://ub-tilvekst.uio.no/
- [[Kildekode]] : https://github.com/scriptotek/alma-newbooks-db
- Status:
	- Hvem bestemmer om denne skal driftes videre?
- Tech: Nginx+PHP+Laravel 7
- Driftes på ub-www01.uio.no : /srv/ub-tilvekst.uio.no , tilgang: ub-utv
- Data i Postgres på USITs databasehotell
- [[Integrasjoner]]
	- Henter rapporter fra [[Alma Analytics]]:
		- /shared/UIO,Universitetsbiblioteket/Reports/Nyhetslister/
		- Autentiserer med API-nøkkelen UBO_READ_ONLY fra https://developers.exlibrisgroup.com/manage/keys/ , som ikke har utløpsdato
- TODO Sende mail til Kristian og Unni om hva vi gjør videre med denne. Forslag: La den leve videre til den dør naturlig, men gjøre minimalt med drift.