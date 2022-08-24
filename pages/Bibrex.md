type:: [[system]]
tech:: php,laravel
status:: [[Må avklares]]
server:: [[ub-www01]]

- URL: https://bibrex.uio.no
- Tech: Nginx+PHP+Laravel 7
- Kildekode: https://github.com/scriptotek/bibrex
- [[Hva må til for at systemet evt. skal kunne fases ut?]]
	- Det må tas en beslutning på ledelsesnivå at Alma skal brukes i stedet
	- Alle utlånsobjekter må flyttes over i Alma
- [[Hva må til for å drifte systemet videre?]]
	- Bibrex er lettdriftet. Databasen driftes av USIT. Applikasjonens rammeverk (Laravel) bør oppdateres én til to ganger i året sammen med andre avhengigheter for å holde applikasjonen sikker. Dette tar typisk noen timer til en halv dag. Applikasjonen har vært i drift i 9 år, men har blitt oppdatert kontinuerlig slik at det ikke er noe etterslep av teknisk gjeld.
	-