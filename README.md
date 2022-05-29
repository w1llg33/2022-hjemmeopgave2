# Hjemmeopgave 2

**Deadline:** 6. juni kl 18.00. 

Se `ho2.pdf` for selve opgaveteksten. 

Du afleverer ved at committe din besvarelse til en mappe, `submission`, hvori der skal ligge en pdf, som indeholder din besvarelse samt kode, som du skal lægge i en undermappe, `submission/kode`. Sørg for, at din kode kan eksekveres - tryk fx "restart kernel and run all" en sidste gang, hvis du bruger jupyter notebook. Sørg også for eventuelt at pakke funktioner væk i separate `.py`-filer, som du importerer i din notebook, så din primære notebook er letlæselig og præsenterer resultater nogenlunde ordentligt. 

Der medfølger lidt kode til at komme i gang med hver af de tre opgaver. 
1. `penalty.ipynb`
2. `collusion.ipynb`
3. `ebay.ipynb`, som skal bruge data fra `ebay_ho2.parquet`. 

Datafilen `ebay_ho2.parquet` hentes fra Absalon og placeres i samme mappe som `ebay.ipynb`. For at kunne indlæse filen, skal du have installeret `pyarrow` og `fastparquet`. Dette gøres ved `conda install pyarrow fastparquet`.  
