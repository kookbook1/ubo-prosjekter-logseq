type:: [[system]]
tech:: docker
server:: [[ubprod01-uxl]] 
brukes-av:: eksterne, [[Emnesøk]] 
status:: [[Driftes videre]]
del-av:: [[Emneordsystemene]]

- Driftes som Docker-containere
	- https://github.com/scriptotek/data.ub.uio.no
- Status:
	- Skosmos er den offentlige inngangen til vokabulerene våre. Vi har ikke noe alternativ til Skosmos.
- Oppgaver:
	- DONE Legge til norsk fortekst for "Generelle se-henvisninger" (plusUseTerm) hvis det ikke allerede finnes
	- DONE Fjerne vokabularene MSC, CCS, Menneskerettighetstermer, Bokbasen
- Drift:
	- Laste inn vokabularer på nytt fra scratch:
		- ```
		  sudo -u ubo-bot bash -l
		  cd /data/vocabs
		  ./load_everything.sh
		  ```