public:: true
query-table:: true
query-properties:: [:page]
#+BEGIN_QUERY
	{:title "Etter status"
     :query [:find (pull ?p [*])
	 :where
         [?p :block/name _]
         (page-property ?p :type "status")
]}
#+END_QUERY

- query-sort-by:: tech
  query-sort-desc:: true
  #+BEGIN_QUERY
  	{:title "Prosjekter"
       :query [:find (pull ?p [*])
  	:where
           [?p :block/name _]
           (page-property ?p :type "prosjekt")
  ]}
  #+END_QUERY
- #+BEGIN_QUERY
  	{:title "Datasett"
       :query [:find (pull ?p [*])
  	 :where
           [?p :block/name _]
           (page-property ?p :type "datasett")
  ]}
  #+END_QUERY
-
- Generelle oppgaver:
	- TODO Spørre USIT om å få lagt inn noen docker images på Harbor, PHP, tilgang til Jenkins for å bygge bilder?