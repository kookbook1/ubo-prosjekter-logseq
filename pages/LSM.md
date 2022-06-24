public:: true
type:: [[prosjekt]]
status:: [[Planlegger utfasing]]
brukes-av:: [[Emnesøk]]
server:: [[ub-www01]]
tech:: nginx, php, laravel

- URL: https://ub-lsm.uio.no/
- Kildekode: https://github.com/scriptotek/lsm
- Driftes på ub-www01.uio.no : /srv/ub-lsm.uio.no , tilgang: ub-utv
- Tech: Nginx+PHP+Laravel 7
- Hva må til for at tjenesten kan fases ut?
	- Finne ut hva som faktisk bruker den
		- [[Emnesøk]]
			- Primo-middlewaren var viktigst tidligere da det var IP-begrensning på Primo-API-et. I dag kan antakelig Emnesøk snakke direkte med Primo REST-API-et.
			- [[Emnesøk]] må først omskrives til å kalle Primo-API-ene direkte. Eller Emnesøk skal avvikles?
		- [[Colligator]]
		- Flere? Undersøke