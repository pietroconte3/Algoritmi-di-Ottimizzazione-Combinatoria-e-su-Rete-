# Algoritmi_di_Ottimizzazione_Combinatoria_e_su_Rete
Algoritmi di clustering applicati a grafi: confronto tra K-Means, Ricerca Locale e Simulated Annealing per l'ottimizzazione della partizione dei nodi su istanze di benchmark

Questo progetto nasce come lavoro per il corso di "Algoritmi di Ottimizzazione Combinatoria e su Rete" (A.A. 2024-2025) e affronta il problema del clustering su grafi, proponendo e confrontando tre diverse tecniche euristiche: **K-Means**, **Ricerca Locale** e **Simulated Annealing**.

## Tecniche Utilizzate

### 1. K-Means
Algoritmo euristico greedy che assegna iterativamente i punti al centroide più vicino. Sono state testate due varianti.

### 2. Ricerca Locale
Partendo da una soluzione iniziale non ottimale, esplora il suo intorno cercando una configurazione migliorativa in termini di *inertia*. Viene interrotta quando non si trovano ulteriori miglioramenti.

### 3. Simulated Annealing
Algoritmo ispirato alla tempra dei metalli: accetta anche soluzioni peggiorative in funzione della temperatura per evitare minimi locali. Si basa su un modello probabilistico di accettazione delle soluzioni.

## Librerie Utilizzate
- `sklearn.cluster.KMeans`
- `numpy`, `matplotlib`
- `time` per la misurazione delle prestazioni

Professore: Maurizio Boccia  
Università Federico II – A.A. 2024-2025
