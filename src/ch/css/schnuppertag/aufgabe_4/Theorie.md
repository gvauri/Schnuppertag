# Theorie für Aufgabe 4

Weiter wollen wir uns mit den Schlaufen auseinandersetzen. Es gibt mehrere Schlaufentypen,
allerdings fokussieren wir uns auf eine.</br>
<b>Grundlagen:</b></br>
Schlaufen werden dazu verwendet um gewisse Abläufe in einem Programm mehrmals auszuführen.</br>
Beispiel einer For-Schlaufe:</br>
<pre>
for(int variabelName = 0; variabelName <= 10; variabelName++){
    System.out.println("Die aktuelle Zahl ist: " + i);
}
</pre>

for() -> for ist ein von Java definiertes Schlüsselwort und kennzeichnet eine For-Schlaufe</br>
int variabelName = 0; -> Erstes Segment, hier kannst du eine Variabel initialisieren.</br>
variabelName <= 10; -> Zweites Segment, hier definierst du die Bedingung, wie lange die Schlaufe andauern soll bis sie fertig ist.
variabelName ++; -> Im dritten Segment, damit die Bedingung irgendeinmal zutrifft, muss der Zustand der Variabel angepasst werden.