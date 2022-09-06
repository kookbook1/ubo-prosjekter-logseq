type:: [[system]]
tech:: php,laravel
server:: [[ub-www01]]
status:: [[Planlegger utfasing (kortsiktig)]]

- Kildekode: https://github.com/uio-library/scroll-app
- Tech: Nginx+PHP+Laravel 7
- [[Hva må til for at systemet evt. skal kunne fases ut?]]
	- Nettstedet inneholder to kurs som evt. må migreres til Canvas:
		- Generell kjemi
			- URL: https://generellkjemi.uio.no/
			- Kildekode: https://github.com/uio-library/generell-kjemi
				- Må bevares iflg. CH (kjemi). Men hvor? Sida kan serves som statisk HTML = enkel drift, men hvor?
				- TODO Finne ut hvor domenet ligger. Kan kanskje peke til en statisk HTML på GitHub Pages?
		- Bibliotek for fysikere
			- URL: https://scroll-app.uio.no/bibliotek-for-fysikere/
			- Kildekode: https://github.com/henriasv/physics-library-course-content
			- 2022-09-01 Møte med Kathinka, Heidi og Line
				- Kan innholdet flyttes til Canvas?
					- H: Mjo. Men Canvas ikke like fleksibelt, må knyttes til kurs. Fint å ha noe som en bare kan dele lenken til uten å måtte lage kurs, registrere studenter osv. Kan ha åpne kurs, men da uten oppgaver. Eksempel: https://richland.instructure.com/courses/1009249/quizzes/1021168?module_item_id=6928377
					- H: Hvis det skal beholdes må det brukes for flere fag.
				- Scroll sist oppdatert for 4 år siden. En mulighet er at DM oppdaterer til nyeste versjon av rammeverk, da kan den antakelig kjøre i 4 år til. Men forutsetter at det er et faktisk ønske om det.
				- L inviterer til arbeidsmøte for å teste overføring til Canvas og avklare om det er behov/ønske om å videreføre Scroll eller ikke.
- [[Anbefaling]]
	- Avvikles høsten 2022
	-