type:: [[system]] [[datasett]]
server:: [[ub-media01]] 
tech:: javascript,php
status:: [[Driftes videre]]
ansvar:: [[Må avklares]]

- [[Sammendrag]]: Datasett produsert av TF (som ligger på GitHub og i et mindre egnet format i Alma Digital) og en enkel applikasjon som ble utviklet fordi Alma Digital ikke var bra nok, som i dag ligger på [[ub-media01]]
- [[URL]]: https://ub-media.uio.no/norske-epitafier-1537-1700/#/
- [[Kildekode]]: https://github.com/uio-library/norske-epitafier
- [[Hva må til for at systemet evt. skal kunne fases ut?]]
	- Ledelsesbeslutning. Må også avklares med TF. Sterk anbefaling at systemet ikke fases ut.
- [[Hva må til for å drifte systemet videre?]]
	- (Med systemet menes applikasjonen. Det er underforstått at datasettet må beholdes uansett)
	- Applikasjonen er en statisk HTML-side, mao. nokså triviell å drifte.
		- Men den bør flyttes til en annen server og noen bør få formelt ansvar for den. Et forslag er å flytte den til [[dsc.ub.uio.no]] sammen med forskningsstøtteprosjektene til [[Kyrre]]
		- [[Integrasjoner]]:
			- Henter data fra [[Alma Digital IIIF Manifest-API]], så den må oppdateres etter eventuelle API-endringer i dette API-et. Siden IIIF er en standard bør det skje svært sjelden, men det skjedde en større endring i begynnelsen av august 2022 som førte til at applikasjonen brakk og måtte bygges på nytt. Dette tok 2 timer å fikse.
	-