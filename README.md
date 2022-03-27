# ztp-rest


## Zadania
1. CounterService (2 punkty)
   * serwis ma być napisany w Javie
   * serwis ma udostępniać enpoint typu `GET` o nazwie `count` przyjmujący parametr `callerId`
   * endpoint ma zwracać liczbę - informację ile razy dany endpoint został wywołany dla danego `callerId`
   * serwis ma kontynuować liczenie po restarcie, tzn. dane mają być przechowywane w bazie danych (przykładowe w `SQLite`)
   * serwis ma działać w kontenerze
2. PersonCounterService (1 punkt)
   * serwis ma być napisany w Pythonie
   * serwis ma udostępniać endpoint typu 'GET' o nazwie `count` przyjmujący parametry `name` oraz `surname` reprezentujące użytkownika
   * endpoint ma zwracać liczbę - informację ile razy dany endpoint został wywołany dla danego użytkownika
   * endpoint ma korzystać z endpointu napisanego w Javie do pobierania liczby wywołań
   * parametry `name` oraz `surname` mają być jednoznacznie (ale w dowolny sposób) konwertowane na `callerId` wymagany przez serwis w Javie
   * serwis ma działać w kontenerze
3. Docker Compose (1 punkt)
   * należy skorzystać z docker compose w celu zbudowania i skonfigurowania oby kontenerów 