# MC-OL48MIAEA31-06
Schema quadro elettrico per ascensore serie `mcpx`. Impianto oleodinamico con emergenza e gestione emendamento A3,
taglie S40-60-70.

Puoi trovare il repository dello schema su
<a href="https://github.com/eca-automs/MC-OL48MIAEA31-06" target="_blank">GitHub</a>.

### Scheda controllo
MCPX2015-SMD - PER16B-SMD

###### Firmware
[P](https://docs.ecaq.in/it/info/mcpx-board-manual-p).

### Tipo impianto
Oleodinamico.

### Manovra
Universale.

### Collegamento vano / cabina
Vano|Cabina
---|---
parallelo|  parallelo

### Operatore porte
Automatico trifase, automatico elettronico, manuale.

### Avviamento / controllo motore
Diretto, stella-triangolo, sift-starter SMS-Start.

### Potenza massima motore / taglie compatibili

#### Avviamento diretto
Taglia|Potenza
---|---
S40|14CV-230VAC/22CV-400VAC

#### Avviamento stella-triangolo
Taglia|Potenza
---|---
S70|24CV-230VAC/43CV-400VAC

#### Avviamento soft-starter
Taglia|Potenza
---|---
S60|17CV-230VAC/35CV-400VAC

### Allarme
12VDC, legge 13, allarme porte aperte fuori piano.

### Emergenza
Totale con riaperture porte tramite scheda SMS miae.

### Emendamento A3
Doppia valvola discesa con controllo tramite boxA3 SMS.
