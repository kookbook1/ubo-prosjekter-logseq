- Etter status:
  query-properties:: [:page]
	- {{query (page-property type [[status]])}}
- Prosjekter:
  query-table:: true
  query-properties:: [:page]
	- {{query (page-property type [[prosjekt]])}}
	  query-properties:: [:page :type :status :server :del-av :brukes-av :tech]
- Datasett:
  query-sort-by:: tech
  query-sort-desc:: true
	- {{query (page-property type [[datasett]] )}}
	  query-properties:: [:page :type :server]
- Generelle oppgaver:
	- TODO Spørre USIT om å få lagt inn noen docker images på Harbor, PHP, tilgang til Jenkins for å bygge bilder?