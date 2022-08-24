type:: [[system]]
status:: [[Planlegger utfasing (langsiktig)]] 
brukes-av:: [[Emnesøk]]
server:: [[ub-www01]]
tech:: nginx, php, laravel

- [[Sammendrag]]: Middleware for å gi enklere tilgang til data fra Alma og Primo for utviklere
- [[URL]]: https://ub-lsm.uio.no/
- [[Kildekode]]: https://github.com/scriptotek/lsm
- [[Hvor bor det?]]
	- `/srv/ub-lsm.uio.no` på [[ub-www01]]
- Tech: Nginx+PHP+Laravel 7
- [[Hva må til for å drifte systemet videre?]]
	- Relativt lettdriftet, men har en del avhengigheter som gjør den mer krevende enn f.eks. [[Bibrex]]
- [[Hva må til for at systemet evt. skal kunne fases ut?]]
	- Finne ut hvilke tjenester som bruker den. Foreløpig oversikt:
		- [[Emnesøk]]
			- Primo-middlewaren var viktigst tidligere da det var IP-begrensning på Primo-API-et. I dag kan antakelig Emnesøk snakke direkte med Primo REST-API-et.
			- [[Emnesøk]] må først omskrives til å kalle Primo-API-ene direkte. Eller Emnesøk skal avvikles?
		- [[Colligator]]
		- Flere? Undersøke