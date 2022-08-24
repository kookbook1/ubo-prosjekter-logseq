type:: [[system]]
status:: [[Driftes videre]]
server:: [[ubprod01-uxl]]
del-av:: [[Emneordsystemene]] 
tech:: python

- Tech: Python + DoIt
- [[Sammendrag]]: Henter MARCXML fra Alma via sftp.bibsys.no, sender data til [[Skosmos]] og til og fra [[CCMapper]]
- [[Kildekode]]:
	- https://github.com/realfagstermer/roald-converters
	- https://github.com/realfagstermer/realfagstermer/
	- https://github.com/scriptotek/humord
- [[Hva må til for å drifte systemet videre?]]
	- Oppdatering av avhengigheter to ganger i året, kanskje noe utvikling etter behov
- [[status]]
	- Bør driftes videre så lenge vi ønsker å publisere emneordsvokabulerene [[Humord]] og [[Realfagstermer]] utad, som jeg mener vi bør.
- Oppgaver
	- DONE Legge til import av 260-feltene (plusUseTerm, generelle se-henvisninger), så de kan vises i skosmos
	- TODO Legge til import fra [[ccmapper]]-ftp
	- TODO Samle i ett repo?