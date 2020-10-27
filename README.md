# IDA

## Git-Kommandos

<!--- TODO: Noch andere Beispiele außer <file> -->

### Anmerkungen

* Vor jedem Kommando kommt "git" (z.B. git add). 
* &lt;file&gt; bedeutet, dass man da irgendeinen file zu schreiben hat. 
* [<irgendwas>] bedeutet, dass es optional ist. Also z.B. commit [-m <comment>] bedeutet, dass man -m <comment> auch auslassen könnte.

### Kommandoliste

* add <file>: <file> wird gestaged. Dass eine Datei gestaged ist bedeutet quasi dass sie für den commit bereit ist. Eine gestagte Datei ist im Versionsverlauf noch nicht gespeichert.
* commit [-m <comment>] <file>: Alle gestageten Dateien werden als neueste Version von Git aufgezeichnet. Ich empfehle, immer -m <comment> zu verwenden, da ihr sowieso auch beim Auslassen davon ein
Commit-Comment eingeben müsst. Der Comment sollte kurz angeben, was für Veränderungen euer Commit bringt.
* 
