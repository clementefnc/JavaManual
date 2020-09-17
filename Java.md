# Java

## Licenza

Questo lavoro è rilasciato sotto licenza **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License**. Per vedere una copia di questa licenza visita http://creativecommons.org/licenses/by-nc-sa/4.0/ o invia una lettera a Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.

![licenza](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)

## Java Environment

Java mette a disposizione construtti OO: definizione di classi in modo gerarchico, creazione/distruzione dinamica, scambio di messaggi.

Non offre costrutti procedurali: non ci sono funzioni o variabili globali.

È indipendente dalla piattaforma, perchè trasformato in linguaggio intermedio (bytecode) e poi interpretato.

É estremamente dinamico e robusto: controlli in compilazione, a run-time, garbage collector e gestione errori a runtime con il meccanismo delle eccezioni.

Supporta generazione della documentazione e raggruppamento in librerie (packages). Include un sacco di utility nelle librerie standard (concorrenza, GUI, networking).

**Classi**: una classe è una rappresentazione astratta di una entità, ne definisce la struttura.

```java
/* MyFirstClass.java */
public class MyFirstClass{
  // Stuff
}
```

**Metodi**: gli strumenti mediante cui è possibile operare sugli oggetti (istanze di classi, ovvero rappresentazioni concrete con specifiche caratteristiche di ciò che è definito da una classe).

Esiste un metodo `main` da cui parte l'esecuzione del programma.

```java
public static void main(String[] args){
  // Stuff
}
```

Una volta compilati i file `.java` si ottengono i file `.class` in bytecode che poi sono eseguibili dalla JVM (Java Virtual Machine) attraverso il comando `java MyFirstClass` ad esempio.

I programmi Java possono essere "*impacchettati* in file **jar** che sono archivi compressi che contengono delle meta-informazioni per specificarne l'esecuzione.

Convenzioni:

- Si usa la **camelBackCapitalization** per nomi composti
- Le classi hanno nomi che iniziano per maiuscola
- Metodi, oggetti, attributi, variabili locali iniziano per minuscola
- Le costanti sono tutte in maiuscolo, se su più parole separate da underscore



