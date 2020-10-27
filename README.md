# IDA

## Git-Kommandos

<!--- TODO: Noch andere Beispiele außer <file> -->

### Anmerkungen

* Vor jedem Kommando kommt "git" (z.B. git add). 
* &lt;file&gt; bedeutet, dass man da irgendeinen file zu schreiben hat. 
* [&lt;irgendwas&gt;] bedeutet, dass es optional ist. Also z.B. commit [-m &lt;comment&gt;] bedeutet, dass man -m &lt;comment&gt; auch auslassen könnte.

### Kommandoliste

* add &lt;file&gt;: &lt;file&gt; wird gestaged. Dass eine Datei gestaged ist bedeutet quasi dass sie für den commit bereit ist. Eine gestagte Datei ist im Versionsverlauf noch nicht gespeichert.
* commit [-m &lt;comment&gt;] &lt;file&gt;: Alle gestageten Dateien werden als neueste Version von Git aufgezeichnet. Ich empfehle, immer -m <comment> zu verwenden, da ihr sowieso auch beim Auslassen davon ein
Commit-Comment eingeben müsst. Der Comment sollte kurz angeben, was für Veränderungen euer Commit bringt.
* clone &lt;url&gt;: Die Repo von dem angegebenen Link wird in dem derzeitigen Ordner, von dem man das Kommando ausführt, gedownloadet und eine Git-Repo initialisiert. Also &lt;url&gt; wäre wohl in unserem Falle https://github.com/HSinger04/IDA.
* pull: Downloadet und updatet die lokale Repository mit der neuesten Version der Online-Repository (i.e. von https://github.com/HSinger04/IDA). Hier kann es sein, dass sogenannte Mergekonflikte entstehen.
* push: Die Online-Repositry wird mit den lokalen Commits / Veränderungen upgedatet. Falls seit dem letzten pull und dem jetztigen push bei der Online-Repo Veränderungen gab, muss man zuerst pull ausführen, bevor man push machen kann. Dabei kommt es eventuell zu Mergekonflikten.   
* mv &lt;file&gt;: Funktioniert so wie normales mv. Nur muss man git mv statt mv verwenden, damit es auch so funktioniert, wie man es sich vorstellt.

#### Versionhistory

* git checkout -- &lt;file&gt;: Verwandelt den Inhalt von &lt;file&gt; zu dem Inhalt des letzten Commits zurück
