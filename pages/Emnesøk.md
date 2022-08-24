type:: [[system]]
tech:: angularjs
server:: [[app-evs]]
del-av:: [[Emneordsystemene]] 
status:: [[Må avklares]]

- [[URL]]: https://app.uio.no/ub/emnesok
- [[Kildekode]]: https://github.com/scriptotek/emnesok
- Noter om drift:
	- Montert som nettverksdisk på [[ubprod01-uxl]]:
		- /net/app-evs/w3-vh/no.uio.www_80/ub/emnesok/htdocs/2
		- /net/app-evs/w3-vh/no.uio.www_80/ub/emnesok/htdocs/data/ureal/rii/admin/
	- Tilgangsgruppe: ub-utv
- Avhengigheter:
	- [[Skosmos]] for autoriteter
	- [[LSM]] for søk mot Oria, vurdere om vi kan bruke Primo-API-et direkte.
- Status:
	- Brukes antakelig mest av våre egne ansatte i veiledning.
	- TODO Dan Michael sender epost til Unni og Kristian og ber dem undersøke ønske om videre drift. Foreslå at vi legger inn en deprecation warning der det er mulig å komme med tilbakemelding for å få tilbakemelding på hvordan den faktisk brukes og kanskje at Kristian tar det videre med avdelingsbibliotekene hvordan bruken er, avklare stakeholders.
- [[Hva må til for å drifte systemet videre?]]
	- Bygget på et rammeverk (AngularJS) som er end-of-life, så burde egentlig vært skrevet på nytt fra scratch. Flere års etterslep på oppdateringer. Dog ingen sikkerhetsrisiko siden det ikke er noen innlogging i tjenesten.
- [[Hva må til for at systemet evt. skal kunne fases ut?]]
	- Ledelsesbeslutning.
- [[Anbefaling]]
	- Undersøke hvor stort ønske det er for å videreføre tjenesten og basert på dette enten gi [[Kyrre]] tid til å modernisere den eller la den leve så lenge den virker, men ikke legge ressurser i oppdateringer.