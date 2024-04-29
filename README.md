Statička analiza SonarLintom:
Calculator.java - linija 1 - Move this file to a named package. sonarlint(java:S1220) (Premestite fajl u paket)
Calculator.java - linija 4 - Add a private constructor to hide the implicit public one.   sonarlint(java:S1118) (Napravite privatni konstruktor za ovu klasu)
Calculator.java - linija 18 - Rename method "ToString" to prevent any misunderstanding/clash with method "toString" defined in superclass "java.lang.Object".sonarlint(java:S1845) (Promenite ime promenljive da ne podseća na toString)
Calculator.java - linija 18 - Rename this method name to match the regular expression '^[a-z][a-zA-Z0-9]*$'.sonarlint(java:S100) (Promeniti ime promenljive)
Calculator.java - linija 24 - Rename this method name to match the regular expression '^[a-z][a-zA-Z0-9]*$'.sonarlint(java:S100) (Promeniti ime promenljive)
Calculator.java - linija 70 - Immediately return this expression instead of assigning it to the temporary variable "textResult".sonarlint(java:S1488) (Dodeljivanje ove promenljive je nepotrebno i ona se može obrisati)
Calculator.java - linija 74 - Rename this method name to match the regular expression '^[a-z][a-zA-Z0-9]*$'.sonarlint(java:S100) (Promenite ime promenljivoj)
Calculator.java - linija 183 - Remove this redundant jump.sonarlint(java:S3626) (return naredba se može obrisati)
Start.java - linija 1 - Move this file to a named package.sonarlint(java:S1220) (Premestite fajl u paket)
Start.java - linija 6 - Rename this local variable to match the regular expression '^[a-z][a-zA-Z0-9]*$'.sonarlint(java:S117) (Promeniti ime promenljivoj)
Start.java - linija 8 - Replace this use of System.out by a logger.sonarlint(java:S106) (Zameniti Sistem.Out.println metodom info iz klase Logger)
Start.java - linija 19 - Replace this use of System.out by a logger.sonarlint(java:S106) (Zameniti Sistem.Out.println metodom info iz klase Logger)

Neformalan pregled:
Aplikacija adekvatno radi i rešava računske zadatke. Ako se unesu pogrešni podaci izbacuje poruku Error i nastavlja da radi. Poželjno bi bilo da program izbacuje više informacija o suštini greške.
LOC Calculator.java=188
LOC Start,java=26
LOC za ceo projekat=214
