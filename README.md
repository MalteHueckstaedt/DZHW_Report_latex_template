# DZHW Report latex template

DZHW Projektbericht template. Grundlage ist der Code von S.Stahlschmidt.

## Nutzung auf OSX

### Vorbereitung

#### Calibri systemweit installieren

Um das `.RMD`-File kompilieren zu können, ist es nötig unter OSX die Schrift `Calibiri` systemweit nutzbar zu machen. Ist **Office Word** bereits installiert, muss hierzu lediglich der entsprechende Schriften-Ordner des Apps aufgerufen werden:

`/Applications/Microsoft Word.app/Contents/Resources/DFonts/`

Anschließend werden sämtliche Varianten von `Calibri` per Doppelklick mittels der Schriftensammlung-App händisch systemweit installiert.

#### Preload Hyphenation Patterns

 tinytex::tlmgr_install("collection-langgerman")`
