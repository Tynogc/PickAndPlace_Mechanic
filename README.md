# PickAndPlace_Mechanic
The Mechanic-Side of an automatic SMT Pick&Place-System

Programm: Siemens-NX Mechanik und Konstruktion eines voll automatischen, schnellen, 4-Spindel SMT-Pick&Place Systems.

Ordner "PickAndPlace": NX-Daten für die Konstruktion, Nomenklatur: (%Bestandteil)(%Nummer)(%V)(%Fertigungsart)(%Material).prt 

%Bestandteile: (Ein Großer Buchstabe)
        A-F Hauptbestandteile nach Größe/Funktion 
        R-T Sonderbestandteile 
        V-Z Normteile
        
%Nummer: Vortlaufende Nummer in einer Bestandteil-Gruppe

%V: Versionierung a-z wenn nicht Benutzt, kein Buchstabe

%Fertigungsart: Großbuchstabe abkürzung der Fertigung; Bei Normteilen nicht füllen D Drehhen F Fräsen

%Material: Material in Volltext/Abkürzung; Bei Normteilen DIN oder Bezeichnung

Ordner "Partlist": Gleiche Struktur wie "PickAndPlace" 
(%Name)_List.txt Liste der Bestandteile Original 
(%Name)_Prototyp.txt Zuordnung der Bauteile zu Verantwortlichen Personen für den Prototyp

Ordner "Other": Sonstige Konstruktionen in Corel-Draw o.ä.
