## ML-project
#### Jelena Vucicevic 1039/2019
# Predvidjanje odobravanja kredita u banci
Za projekat su korisceni podaci task_two.csv sa hackhatona jedne lokalne banke. Cilj je da se nadje najbolji model koji predvidja da li ce zahtev
za kredit biti odobren na osnovu karakteristika o podnosiocu zahteva. Ceo rad se nalazi u jednoj Jupyter svesci sa sledecim sadrzajem:

1.  EDA
    - Osnovna analiza podataka
    - Vizuelna analiza podataka
    - Tretman autlajera
    - Dopunjavanje podataka koji nedostaju
2. Odabir atributa
   - Vizuelna procena
   - ANOVA
3. Priprema podataka za treniranje modela
   - Pretvaranje binarne nominalne varijable u numericku pomocu 1/0 preslikavanja
   - Pretvaranje nominalne varijable u numericku pomocu get_dummies() funkcije
   - Podela podataka za treniranje i testiranje
   - Sandardizacija
4. Modeli
   - Logisticka Regresija
   - Random Forest
   - AdaBoost
   - XGBoost
   

Od nestandardnih biblioteka neophoodne su sledece:
- pip install xgboost
- pip install missingno

Literatura i korisceni sajtovi za izradu projekta:
- https://medium.com/
- https://stackoverflow.com/
- freeCodeCamp.org

          
     
     
     
