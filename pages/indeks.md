- Etter status:
  query-properties:: [:page]
	- {{query (page-property type [[status]])}}
	  query-properties:: [:page :definisjon]
	  query-sort-by:: definisjon
	  query-sort-desc:: true
- Systemer:
  query-table:: true
  query-properties:: [:page]
	- {{query (page-property type [[system]])}}
	  query-properties:: [:page :type :status :server :del-av :brukes-av :tech]
- Servere:
	- {{query (page-property type [[server]] )}}
	  query-properties:: [:page :type]
- Datasett:
  query-sort-by:: tech
  query-sort-desc:: true
	- {{query (page-property type [[datasett]] )}}
	  query-properties:: [:page :type :server]
- [[rt-bot]]
- Generelle oppgaver:
	- TODO Spørre USIT om å få lagt inn noen docker images på Harbor, PHP, tilgang til Jenkins for å bygge bilder?