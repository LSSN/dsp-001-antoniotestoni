# Esercizi di DSP - 01

##### 1. Scrivi un programma che utilizzi i quattro operatori matematici in parallelo

```
import("stdfaust.lib");
process = _+_,_*_,_-_,_/_;
```

##### 2. Scrivi un programma che utilizzi i quattro operatori matematici in serie

```
import("stdfaust.lib");
process =_+_:_-(0.5):_*(2):_/(2);
```

##### 3. Scrivi un programma che esegua due operazioni in sequenza e producano un segnale in uscita identico a quello in entrata

```
import("stdfaust.lib");
process = *(1): *(1);
```

##### 4. Scrivi un programma che abbia 4 segnali un entrata, ne dimezzi l'ampiezza e li porti in uscita su quattro canali separati

```
import("stdfaust.lib");
process = /(0.5),/(0.5),/(0.5),/(0.5):_,_,_,_;
```

##### 5. Scrivi un programma che abbia 4 entrate ed una sola uscita, somma delle 4 entrate.

```
import("stdfaust.lib");
process =
```
