type:: [[prosjekt]]
status:: [[Driftes videre]]
server:: [[ubprod01-uxl]]
del-av:: [[Emneordsystemene]] 
tech:: python

- Tech: Python + DoIt
- Henter MARCXML fra Alma via sftp.bibsys.no, sender data til Skosmos og CC Mapper
- Kildekode:
	- https://github.com/realfagstermer/roald-converters
	- https://github.com/realfagstermer/realfagstermer/
	- https://github.com/scriptotek/humord
- Oppgaver
	- DONE Legge til import av 260-feltene (plusUseTerm, generelle se-henvisninger), så de kan vises i skosmos
	- TODO Legge til import fra [[ccmapper]]-ftp
	- TODO Samle i ett repo?