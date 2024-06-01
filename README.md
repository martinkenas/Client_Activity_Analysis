## Duomenų Analizė

- **Svarbūs Požymiai:** Duomenų analizė atskleidė, kad kliento amžius, išlaidos vynui, šeimos statusas (numanomas pagal vaisių ir žuvies pirkimus) bei aktyvumas internete yra svarbūs veiksniai, lemiantys atsaką į rinkodaros kampanijas.
- **Klasės Disbalansas:** Duomenyse buvo pastebėtas reikšmingas klasių disbalansas, kai klientų, nereagavusių į kampanijas, buvo žymiai daugiau nei reagavusių.

## Modelių Kūrimas ir Palyginimas

- **Įvairūs Modeliai:** Buvo sukurti ir įvertinti trys skirtingi modeliai: logistinė regresija, atsitiktinių miškų algoritmas ir XGBoost.
- **Hiperparametrų Optimizavimas:** Kiekvieno modelio hiperparametrai buvo optimizuoti naudojant kryžminį patikrinimą ir "Grid Search" metodą.
- **ROC Kreivės:** ROC kreivės buvo naudojamos vizualiai palyginti modelių veikimą, parodant jų jautrumą ir specifiškumą.
- **Metrikos:** Modeliai buvo įvertinti pagal AUC-ROC, tikslumą (accuracy), preciziškumą (precision), atkūrimą (recall) ir F1 įvertį.

### Geriausias Modelis

XGBoost: XGBoost modelis pasirodė esąs geriausias atsižvelgiant į visus kriterijus, nors visi modeliai parodė panašius rezultatus.

### Apribojimai

Nepaisant gero bendro veikimo, modeliai vis dar sunkiai identifikuoja klientus, kurie reagavo į kampanijas (mažas recall). Tai gali būti dėl duomenų klasių disbalanso.



