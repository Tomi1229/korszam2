# Kézzel írt karakterek
Egy ismert és gyakori probléma, hogy kézzel írt számokat ismer fel a neurális hálózat. Erre létezik egy általánosan elterjedt adathalmaz az mnist. A deep learning egyik "hello world!" problémája ez, így rengeteg megoldás és példakód található az interneten ennek megoldására.

## Feladatok
Egy jegyzőkönyv elkészítése amelyben egy, a feladatot jól megoldó modell paramétereit változtatjuk. Vizsgáljuk meg, hogy milyen hatásai vannak a következők közül néhánynak:

- Neuronok számának változtatása
- Rétegek változtatása (rétegek hozzáadása/lecserélése, aktivációs függvények változtatása)
- Költség függvények változtatása
- Tanítási paraméterek állítása(epoch szám, batchsize, learning rate)  

A feladat lényege nem az, hogy minél hosszabb jegyzőkönyv készüljön. Ezért nem kell a fentiek közül minden kombinációt kipróbálni, elég csak minimum 4 külön kísérletet megvalósítani. Ezt jegyzőkönyvhöz hasonló módon tegyétek, azaz minden ábra, tanítási ciklus után egy markdown cellába írjátok le, hogy mi történt, szerintetek miért így történt.  
### Például:
 Beleraktunk plusz kétmillió neuront, nem lett jobb az eredmény, de cserébe sokkal lassabb. Ez azért van, mert ... 
### A házi feladatot jupyter notebook formájában szeretnénk kérni!

## Egyéb információk
Az órán tensorflow keretrendszert használtunk, mert tapasztalataink szerint egyszerűbb elindulni bennne. Mindenkinek szíve joga máshogy gondolni. Aki esetleg pytorchban, vagy más keretrendszerben szeretne dolgozni, nyugodtan megteheti. Akinek kérdése van, keressen nyugodtan teamsen vagy emailben.  
  
Pár hasznos link:
- https://www.tensorflow.org/
- https://nextjournal.com/gkoehler/digit-recognition-with-keras
- https://machinelearningmastery.com/how-to-develop-a-convolutional-neural-network-from-scratch-for-mnist-handwritten-digit-classification/

# Határidő: 2022. 11. 28