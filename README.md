### [Die Datensätze in diesem Repositäry sind Open Source. Ich bin jedoch kein Urheber!] ###

### Kurs Neuronale Netze, 28.10.2021

## Anleitung zur Installation der packages

### In Visual Studio Code:

Öffne ein Terminal in einem conda environment

```
conda create -n p37env python=3.7
conda activate p37env
```

und anschließend das Fenster aktualisieren:

```
Shift + cmd + P -> Restart Window, und Python 3.7.11 als Interpreter wählen
```

Nun solltet ihr Tensorflow und Keras installieren können

```
conda install tensorflow
conda install keras
conda install scikit-learn
conda install pandas
conda install matplotlib
```

### Im Anaconda Navigator/ Jupyter Notebook:

1. Öffne den Anaconda Navigator und klicke links auf "Environments"
2. Klicke unten auf "Create"
3. Erstelle das Environment mit dem Namen "p37env" und mit der Python Version 3.7.11
4. Wähle das gerade erstellte Environment aus, klicke auf den grünen Pfeil und wähle "Open Terminal"

5. Gib folgende Befehle in die nun geöffnete Kommandozeile ein:

```
conda install tensorflow
conda install keras
conda install scikit-learn
conda install pandas
conda install matplotlib
```

6. Gehe nun zurück auf "Home" (links im Anaconda Navigator". Öffne "Notebook" (muss beim Anklicken installiert werden). Nun kannst du im Ordner deiner Wahl oben rechts auf 

```
"New" -> Python 3.7.11 64-bit ('p37env': conda)
```

ein Notebook in dem neuen Environment erstellen. Jetzt kannst du die jeweiligen Module importieren.

7. Um ein heruntergeladenes Skript zu benutzen, wähle vor dem Ausführen

```
Kernel -> Change Kernel -> Python 3.7.11 64-bit ('p37env': conda)
```
