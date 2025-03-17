# **WorldEdit**

Trovate una descrizione più completa di tutti i comandi [qui](https://minecraft-worldedit.fandom.com/wiki/Worldedit_Commands).

## **Selezione**

Uno dei modi principali per modificare i mondi
con WorldEdit è tramite Selezione. Esso
consiste semplicemente nel selezionare un'area
da modificare e applicarci dei comandi sopra.
Ci sono due metodi principali per la Selezione:
tramite **wand** e a **selezione manuale**.

### **Wand**

È il modo piú veloce ed efficiente per
effettuare una selezione. Consiste nel creare
un tool (appunto, la "Wand") che vi permette di
selezionare direttamente i blocchi che
delimitano la selezione. La Wand puó essere
qualsiasi tool (spade, asce, picconi...) e
anche alcuni oggetti (come bastoni). Avete due
modi per ottenere una wand:

- Con il comando `//wand`, vi verrà assegnata
  un'ascia di legno come Wand.
- Con il comando `//setwand`, l'oggetto che
  avete in mano diventerà la vostra Wand (a patto
  che sia un oggetto supportato).

Una volta che avete una Wand, potete farci
quello che volete: enchantarla, rinominarla,
darla via, non importa. Se volete che torni un
oggetto normale, tenetela in mano e usate il
comando `//delwand`.

Adesso, per effettuare la selezione, basta fare
un clic sinistro sul primo punto dell'area (la
pos1) e clic sinistro sul secondo (pos2). Tutta
la sezione delemitata dai due punti che avete
scelto diventerà la vostra selezione.

### **Selezione manuale**

Potete anche selezionare l'area che desiderate
manualmente. Spostate il vostro personaggio sul
primo punto che volete selezionare, ed eseguite
il comando `//pos1`, poi andate sulla seconda e
fate `//pos2`.

In alternativa, con `//hpos1` e `//hpos2`
selezionate automaticamente i blocchi che state
guardando come posizioni 1 e 2.

## **Comandi su selezioni**

Una volta che avete selezionato la vostra area, potete iniziare ad usare i seguenti comandi su di essa:

| Comando                       | Descrizione                                                                                                          |
| ----------------------------- | -------------------------------------------------------------------------------------------------------------------- |
| `//desel`                     | Cancella la vostra selezione.                                                                                        |
| `//set <block>`               | Riempie tutta l'area selezionata con <block\>.                                                                       |
| `//replace <block1> <block2>` | Rimpiazza tutti i <block1\> nell'area con <block2\>.                                                                 |
| `//overlay <block>`           | Aggiunge uno strato di <block\> sull'area.                                                                           |
| `//faces <block>`             | Riempie le facce della selezione con <block\>, creando un cubo vuoto.                                                |
| `//walls <block>`             | Riempie le mura attorno alla selezione con <block\>.                                                                 |
| `//regen`                     | Resetta l'area selezionata al suo stato iniziale, al modno piatto che era prima che iniziassimo a costruirci dentro. |
| `//forest <type> <density>`   | Pianta degli alberi di tipo <type\> nell'area con densità <density\>.                                                |
| `//flora <density\>`          | Pianta fiori e piante nell'area con densità <density\>.                                                              |
