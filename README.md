# Epedemie-Simulation


In dieser Stunde haben wir mit dem Programm Star Logo TNG eine Epedemie simuliert. 
Dafür kreierten wir 300 Agenten, die grün eingefärbt sind.

Screenshot 1 einfügen

Damit eine Epedemie ausgelöst werde kann, muss ein Krankheitserreger in den Umlauf gebracht werden. Das geschieht mit Hilfe eines "Infect-Blocks". In diesen setzten wir die Bedingung ein, dass aus hundert Angenten bis zu zehn zufällig infeziert werden und dann ihre Farbe in rot ändern.

Screenshot 2 einfügen

Durch "Kollisions-Blöcke" werden nun auch andere Agenten, die vorher gesund (und grün) waren, infiziert und ändern ihre Farbe in rot.
Dies passiert allerdings nur wenn der Kollisationspartner krank (und rot) ist. Diese Bedingung konnten wir durch einen "If-Block" programmiert
