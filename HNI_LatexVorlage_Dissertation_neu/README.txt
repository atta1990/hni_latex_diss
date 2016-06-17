Vorlage Studentischer Arbeiten

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%  Allgemeine Kommentare
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%Dieses Dokument ist f�r die Verwendung von pdf-latex geschrieben. Dies muss f�r die Kompilierung beachtet werden. Falls das normal Latex verwendet werden soll, m�ssen die Bilder in ps/eps Format vorliegen. 

%Beim Anlegen von gro�en Dokumenten bietet es sich an, nicht alles in eine Datei zu schreiben. Latex bietet hier die M�glichkeit einzelne Dateien durch \input{Dateiname.tex} einzubinden. Man kann also f�r z.B. jedes Kapitel eine eigene Datei schreiben. In diese Datei geh�rt aber nicht der ganze Vorspann (Definition von packages etc...). Hierdurch ist es auch einfach m�glich nur Teile der gro�en Arbeit anzusehen, indem man die anderen \input Befehle auskommentiert. F�r jedes Kapitel sollte eine eigene Texdatei angelegt werden, die in "gliederung.tex" mit eingebunden werden.

%H�ufig m�chte man nur schnell seine �nderungen im Dokument ansehen, aber das Kompilieren dauert wegen der vielen Bilder sehr lange. Hier kann man ganz oben in die documentclass als weitere Option draft einf�gen. Dann werden anstatt der Bilder nur K�sten im Dokument erzeugt und das Kompilieren geht sehr viel schneller. 

%Es ist sehr wichtig darauf zu achten Abs�tze und leere Zeilen geeignet zu verwenden. Wenn ein Absatz gew�nscht ist, muss eine leere Zeile im tex Dokument erzeugt werden, welche nicht mit \\ abgesetzt wird! Ansonsten muss auf leere Zeilen verzichtet werden, da diese sonst zus�tzliche freie R�ume erzeugen. Vor allem beim Schreiben von Formeln sind leere Zeilen wegen der �bersicht h�ufig eingef�gt. Diese m�ssen entfernt oder durch ein % auskommentiert werden. �hnliches ist beim Einbinden von Figures zu beachten. 

%F�r Literaturreferenzen k�nnen wir euch die Programme JabRef oder Citavi empfehlen. Dort kann man sehr einfach die einzelnen Eintr�ge machen und die dadurch entstandene Bibliothek einbinden. 

%Als Editor f�r die Arbeit mit Tex hat sich Texstudio bei uns etabliert. Ein gro�er Vorteil ist, dass man den Tex Code und das eigentliche Dokument nach der Kompilierung nebeneinander sieht und es lassen sich auch sonst noch viele nette Sachen einstellen. Zum Beispiel versteht TexStudio sogenannte Magic-Comments, die den Compiler-Aufruf und die Dateikodierung festlegen lassen. Beim ersten Kompilieren ist der Vertrauenabfrage des Editors zuzustimmen. F�r die Verwendung des Befehls "makeglossaries", welcher eine sehr einfache Generierung der Abk�rzungs- und Symbolverzeichnisse erm�glicht, muss Perl (z.B. activeperl) installiert sein. Alle genannten Programme kann man kostenlos im Internet erhalten (Citavi �ber die Bibo).

%Der Benutzer der Vorlage muss nur folgende Dateien bearbeiten:
%myData.tex
%abstract_de.tex
%abstract_en.tex
%gliederung.tex
%einleitung.tex 
%kapitel_xy.tex (alle Kapitel)
%notation.tex
%anhang.tex


%Viel Vergn�gen beim Schreiben Eurer Dissertation w�nschen,
%Martin, Julia, Christopher und Phillip

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%