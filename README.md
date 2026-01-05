# Customer Segmentation with K-Means Clustering 📊

## 🎯 Obiettivo del Progetto
L'obiettivo è segmentare una base clienti di oltre 8.900 titolari di carte di credito per definire strategie di marketing mirate. Il progetto trasforma dati transazionali grezzi in profili comportamentali azionabili.

## 🛠️ Tech Stack
* **Python** (Pandas, NumPy)
* **Scikit-Learn** (K-Means Clustering, StandardScaler)
* **Data Visualization** (Matplotlib, Seaborn)

## 💡 Workflow Analitico

### 1. Data Cleaning & Imputation
Gestione dei valori mancanti e analisi delle anomalie transazionali per garantire l'integrità del dato.

### 2. Modellazione e Logica di Clustering
Implementata una funzione personalizzata per il calcolo della *Sum of Squared Distances* (SSD).

<img src="img/Plot_curve_Function.png" width="100%" alt="Snippet Funzione SSD Plot">

Attraverso l'**Elbow Method**, è stato individuato il punto di flesso ideale (K=4).

<img src="img/Elbow.png" width="100%" alt="Elbow Method">

### 3. Strategia di Segmentazione
Suddivisione della clientela basata sul `BALANCE` (sotto/sopra 5000 USD) per isolare i comportamenti di spesa estremi.

### 4. Analisi Distribuzione Cluster
Utilizzo di **KDE Plots** per analizzare la densità e la separazione dei segmenti.

<img src="img/KDE_Balance.png" width="100%" alt="KDE Balance Analysis">

## 📈 Risultati Strategici
L'analisi ha permesso di identificare cluster specifici su cui concentrare il budget marketing:
* **Cluster A0 & B2**: Alta propensione agli acquisti (Fidelizzazione).
* **Cluster A2 & B0**: Potenziale indebitamento residuo (Rateizzazione).
* **Ottimizzazione Risorse**: Identificazione cluster a bassa reattività (A1, B3).

---
**Analisi a cura di:** Massimiliano Izzo
