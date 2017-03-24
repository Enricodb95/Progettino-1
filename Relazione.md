# Relazione per il primo progettino
Autori : Enrico Dal Ben, Haki Dine

## Parte I : Creazione di un terreno basato su heightmap
Autore : Enrico Dal Ben

### Codice iniziale
Partendo dal codice iniziale fornito dal Professor Ranon nel file StartingCode-nolights.html ho creato un cubo di base con la texture inspirata ai cubi di Minecraft.
Utilizzando il codice presente nel file StartingCode-heightmap.html ho capito come calcolare il colore di un pixel in una heightmap e come ritornare un vettore contenente i dati sulla tonalità di grigio utilizzando la funzione *getHeightData(img)*.

[Cubo iniziale](textures/cubo.jpg)

### Sviluppo
Partendo dal cubo iniziale, con texture applicata, ho creato inizialmente un ciclo che mi andava a clonare l'oggetto e poi ha spostarlo nella posizione corretta creando inizialmente un terreno piatto.
Sviluppando ulteriormente questa funzione in una funzione chiamata *CreateTerrain(width, height, data)* ho aggiunto i cubi e combinando il risultato fornito da *getHeightData(img)* sull'immagine, ho modificato la loro coordinata y per adattarla al colore del pixel : più chiaro è il pixel più in alto si troverà il cubo.

![risultato intermedio](textures/complete.jpg)



![Risultato finale](textures/complete.jpg)

## Parte II : Movimenti di camera e creazione di un video post-procesato
Autore : Hake Dine
