# Theorie für Aufgabe 3

Du möchtest nun etwas in die Konsole schreiben und das ganze dann als Variable speichern. Dazu kannst du in Java einfach einen Scanner verwenden.
<pre>
Scanner scanner = new Scanner(System.in);
</pre>
Jetzt hast du jedoch erst einen Scanner erstellt, aber noch nichts aus der Konsole ausgelesen. Verwende zum Auslesen einfach folgenden Codeschnipsel:
<pre>
scanner.nextLine();
</pre>
Das Ganze kannst du dann natürlich auch in eine Variable abspeichern oder direkt weiter verarbeiten.
