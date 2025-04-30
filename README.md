# U-Net Image Segmentation Project

Questo progetto implementa un modello U-Net per la segmentazione di immagini, utilizzando dataset personalizzati e librerie Python di deep learning e computer vision. Il notebook principale (`CI_Unet_model.ipynb`) guida attraverso tutte le fasi del processo: dal caricamento dei dati all'addestramento del modello, fino alla visualizzazione dei risultati.

## 📁 Struttura del Progetto

- `CI_Unet_model.ipynb` — Notebook principale contenente tutto il flusso del progetto
- `README.md` — Descrizione del progetto e delle tecnologie utilizzate

## 🔧 Tecnologie Utilizzate

- **Linguaggio**: Python 3.x
- **Deep Learning**: TensorFlow, Keras
- **Computer Vision**: scikit-image, OpenCV (eventualmente)
- **Visualizzazione**: Matplotlib, Seaborn, Plotly
- **Gestione dati**: NumPy, Pandas, PIL
- **Metriche**: Matrice di confusione, Accuracy, ecc.

## 🧪 Fasi del Progetto

1. **Importazione librerie**  
   Vengono caricate tutte le librerie necessarie per il pre-processing, la costruzione del modello e l’analisi dei risultati.

2. **Caricamento e Pre-processing dei Dati**  
   Le immagini e le maschere vengono caricate, ridimensionate e normalizzate per l’addestramento del modello.

3. **Suddivisione del Dataset**  
   Il dataset viene diviso in training e test set con `train_test_split`.

4. **Costruzione del Modello U-Net**  
   Viene costruita un’architettura U-Net classica con livelli di convoluzione, max pooling e upsampling.

5. **Addestramento del Modello**  
   Il modello viene addestrato su dati segmentati con funzione di perdita e metrica di valutazione.

6. **Valutazione e Visualizzazione Risultati**  
   Risultati e maschere previste vengono visualizzate per confrontare le performance del modello.

## 🧠 Obiettivi

- Sperimentare l’uso di U-Net per la segmentazione di immagini
- Valutare performance e qualità delle maschere predette
- Familiarizzare con le librerie di deep learning per compiti di segmentazione

## ✅ Requisiti

Assicurati di avere installato:

```bash
pip install tensorflow keras scikit-image matplotlib seaborn numpy pandas plotly
