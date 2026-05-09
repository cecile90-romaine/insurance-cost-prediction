# insurance-cost-prediction
Ho sviluppato un progetto di Machine Learning su Dataiku con l’obiettivo di prevedere il costo sanitario annuale dei clienti di una compagnia assicurativa.  Il progetto appartiene al settore assicurativo/sanitario e utilizza un modello di regressione per stimare i costi medici futuri degli assicurati.
Insurance Cost Prediction – Machine Learning Project (Dataiku + Python)

 
Obiettivo del Progetto
Il progetto ha l’obiettivo di prevedere il costo sanitario annuale dei pazienti utilizzando tecniche di Machine Learning.
L’obiettivo business è supportare le compagnie assicurative nella:
    • definizione dei premi assicurativi
    • gestione del rischio
    • identificazione dei clienti ad alto costo sanitario
 Panoramica del Progetto
Questo progetto simula un vero caso aziendale nel settore assicurativo utilizzando dati reali Kaggle.
Variabile target:
    • charges (costo sanitario annuale)
 Workflow di Machine Learning (Dataiku DSS)


Il progetto è stato sviluppato utilizzando la piattaforma Dataiku e segue queste fasi:
    1. Importazione dataset
    2. Data Cleaning
    3. Feature Engineering
    4. Encoding variabili categoriche
    5. Split training/test
    6. Training modelli ML
    7. Valutazione performance
    8. Deploy modello
    9. Predizione su nuovi dati
 Feature Engineering
Sono state create nuove variabili per migliorare il modello:
    • age_group (fasce di età)
    • bmi_class (classificazione BMI)
    • has_children (flag presenza figli)


Modelli Utilizzati
Sono stati confrontati due modelli:


1. Linear Regression
    • modello interpretabile
    • buona baseline
2. Random Forest Regression
    • migliore performance
    • cattura relazioni non lineari
Il modello migliore è risultato: Random Forest
Valutazione del Modello
Metriche utilizzate:
    • R² Score
    • Analisi errore predittivo
 Feature Importance
Le variabili più influenti sul costo sanitario sono:
    • smoker (fattore principale)
    • bmi
    • age
 Test su Nuovi Dati
Il modello è stato testato su nuovi clienti simulati utilizzando una pipeline di scoring.
Output:
    • predizione del costo sanitario per ogni cliente
 Insight di Business
    • I fumatori hanno costi significativamente più alti
    • L’età aumenta il costo sanitario
    • BMI elevato è correlato a costi maggiori
Struttura del Progetto
    • Dataiku Flow (pipeline completa)
    • Dataset originale Kaggle
    • Dataset preprocessato
    • Modello ML salvato
    • Dataset predizioni finali
 Tecnologie Utilizzate
    • Dataiku DSS
    • Python
    • Pandas
    • Scikit-learn
    • Machine Learning (Regression Models)
 Sviluppi Futuri
    • Aggiunta di modelli avanzati (XGBoost, LightGBM)
    • Deployment API del modello
    • Dashboard interattiva (Power BI / Streamlit)
    • Automazione pipeline ML
Conclusione
Questo progetto rappresenta un workflow completo di Data Science:
dalla raccolta dati fino alla predizione e interpretazione business-ready.
Autore
Cecile Mbazoa
Studentessa Data Analyst
Interessi: Machine Learning, Data Science, Modellazione dei sistemi informatici
