Vorlage Studentischer Arbeiten

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%  Allgemeine Kommentare
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%Dieses Dokument ist für die Verwendung von pdf-latex geschrieben. Dies muss für die Kompilierung beachtet werden. Falls das normal Latex verwendet werden soll, müssen die Bilder in ps/eps Format vorliegen. 

%Beim Anlegen von großen Dokumenten bietet es sich an, nicht alles in eine Datei zu schreiben. Latex bietet hier die Möglichkeit einzelne Dateien durch \input{Dateiname.tex} einzubinden. Man kann also für z.B. jedes Kapitel eine eigene Datei schreiben. In diese Datei gehört aber nicht der ganze Vorspann (Definition von packages etc...). Hierdurch ist es auch einfach möglich nur Teile der großen Arbeit anzusehen, indem man die anderen \input Befehle auskommentiert. Für jedes Kapitel sollte eine eigene Texdatei angelegt werden, die in "gliederung.tex" mit eingebunden werden.

%Häufig möchte man nur schnell seine Änderungen im Dokument ansehen, aber das Kompilieren dauert wegen der vielen Bilder sehr lange. Hier kann man ganz oben in die documentclass als weitere Option draft einfügen. Dann werden anstatt der Bilder nur Kästen im Dokument erzeugt und das Kompilieren geht sehr viel schneller. 

%Es ist sehr wichtig darauf zu achten Absätze und leere Zeilen geeignet zu verwenden. Wenn ein Absatz gewünscht ist, muss eine leere Zeile im tex Dokument erzeugt werden, welche nicht mit \\ abgesetzt wird! Ansonsten muss auf leere Zeilen verzichtet werden, da diese sonst zusätzliche freie Räume erzeugen. Vor allem beim Schreiben von Formeln sind leere Zeilen wegen der Übersicht häufig eingefügt. Diese müssen entfernt oder durch ein % auskommentiert werden. Ähnliches ist beim Einbinden von Figures zu beachten. 

%Für Literaturreferenzen können wir euch die Programme JabRef oder Citavi empfehlen. Dort kann man sehr einfach die einzelnen Einträge machen und die dadurch entstandene Bibliothek einbinden. 

%Als Editor für die Arbeit mit Tex hat sich Texstudio bei uns etabliert. Ein großer Vorteil ist, dass man den Tex Code und das eigentliche Dokument nach der Kompilierung nebeneinander sieht und es lassen sich auch sonst noch viele nette Sachen einstellen. Zum Beispiel versteht TexStudio sogenannte Magic-Comments, die den Compiler-Aufruf und die Dateikodierung festlegen lassen. Beim ersten Kompilieren ist der Vertrauenabfrage des Editors zuzustimmen. Für die Verwendung des Befehls "makeglossaries", welcher eine sehr einfache Generierung der Abkürzungs- und Symbolverzeichnisse ermöglicht, muss Perl (z.B. activeperl) installiert sein. Alle genannten Programme kann man kostenlos im Internet erhalten (Citavi über die Bibo).

%Der Benutzer der Vorlage muss nur folgende Dateien bearbeiten:
%myData.tex
%abstract_de.tex
%abstract_en.tex
%gliederung.tex
%einleitung.tex 
%kapitel_xy.tex (alle Kapitel)
%notation.tex
%anhang.tex


%Viel Vergnügen beim Schreiben Eurer Dissertation wünschen,
%Martin, Julia, Christopher und Phillip

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%