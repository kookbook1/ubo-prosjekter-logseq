type:: [[system]]
status:: [[Driftes videre]]
server:: [[ubprod01-uxl]]
del-av:: [[Emneordsystemene]] 
tech:: python

- Tech: Python + DoIt
- [[Sammendrag]]: Henter inn Humord MARCXML fra Alma via sftp.bibsys.no, Realfagstermer fra [[Roald + Sonja]], L-skjema MARCXML fra Erik og WebDewey MARCXML fra Pansoft FTP, konverterer alle til lenkede data (RDF) og publiserer dataene på [[data.ub.uio.no]] for [[Skosmos]] og [[Emnesøk]], og sender data til [[CCMapper]].
- [[Kildekode]]:
	- https://github.com/realfagstermer/roald-converters - konverteringspakke som brukes av de ulike vokabularene
	- https://github.com/realfagstermer/realfagstermer/
	- https://github.com/scriptotek/humord
	- https://github.com/realfagstermer/lskjema
	- https://github.com/scriptotek/usvd
	- https://github.uio.no/dmheggo/wdno (WebDewey, lukket pga. rettigheter)
- [[Hva må til for å drifte systemet videre?]]
	- Oppdatering av avhengigheter to ganger i året, kanskje noe utvikling etter behov
- [[status]]
	- Bør driftes videre så lenge vi ønsker å publisere emneordsvokabulerene [[Humord]] og [[Realfagstermer]] utad, som jeg mener vi bør.
- Oppgaver
	- DONE Legge til import av 260-feltene (plusUseTerm, generelle se-henvisninger), så de kan vises i skosmos
	- TODO Legge til import fra [[ccmapper]]-ftp
	- TODO Samle i ett repo?