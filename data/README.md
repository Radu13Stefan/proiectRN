2.1 Sursa datelor

* **Origine:** Datele sunt colectate dintr-un model simplificat al unei retele electrice realizat in LabView
  
* **Modul de achiziție:** ☐ Senzori reali / ☑ Simulare / ☐ Fișier extern / ☐ Generare programatică
  
* **Perioada / condițiile colectării:** [Noiembrie 2025 - Decembrie 2025]

### 2.2 Caracteristicile dataset-ului

* **Număr total de observații:** [Ex: 67000]
* **Număr de caracteristici (features):** [7]
* **Tipuri de date:** ☑ Numerice / ☐ Categoriale / ☐ Temporale / ☐ Imagini
* **Format fișiere:** ☑ CSV / ☐ TXT / ☐ JSON / ☐ PNG / ☐ Altele: [...]

### 2.3 Descrierea fiecărei caracteristici

| **Caracteristică** | **Tip** | **Unitate** | **Descriere** | **Domeniu valori** |
|-------------------|---------|-------------|---------------|--------------------|

| timp | numeric | secunda | [Momentul inregistrarii masuratorii, folosit pentru ordonarea datelor si definirea ferestrelor de timp] | 0–1.0e7 |
| tensiune | numeric | volt | [Tensiunea instantanee masurata in punctl de interes al retelei] | 180-260 V/ 10-20kV |
| curent | numeric | amper | [Curentul electric instantaneu prin conductor/echipament, indica nivelul de incarcare si suprasarcinile] | 0–500 A |
| temperatura | numeric | kelvin | [Temperatura carcasei sau a unui punct critic, pentru depistarea supraincalzililor] | 250-390 K |
| vibratie | numeric | hertz | [Frecventa principala a vibratiilor masurate pe echipamente, asociata uzurii mecanice] | 0-25  |
| sarcina | numeric | coulomb | [Sarcina electrica transferata intr-un interval, corelata cu gradul de solicitare] | 0–150% |
| evenimente | categorial | adimennsional | [Codul evenimentului asociat inregistrarii] | normal, warning, alarm, fault |



