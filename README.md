# sketchToCad

Plugin di istruzioni per Codex/ChatGPT: ricostruisce schizzi tecnici in DXF nativi per AutoCAD e LT. Non e un add-in eseguibile dentro AutoCAD.

## Uso
Seleziona il plugin, allega uno schizzo e chiedi la creazione del DXF. Servono un ambiente con accesso ai file e Python/ezdxf, oppure strumenti CAD equivalenti. Il plugin non include servizi API, credenziali o dipendenze binarie.

## Convenzioni
Millimetri 1:1; Ri=spessore, Re=2x spessore; DIMENSION native senza testi duplicati; LEADER/MTEXT o MULTILEADER; HATCH 45 gradi con passo perpendicolare 2 mm; fissaggi in blocchi; layer separati. Le ipotesi dimensionali vanno dichiarate.

