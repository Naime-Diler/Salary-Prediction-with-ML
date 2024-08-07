# Salary Prediction with Machine Learning

## Projektübersicht

Dieses Projekt beschäftigt sich mit der Vorhersage von Gehältern von Baseballspielern auf Basis von Gehaltsinformationen und Karrierestatistiken aus dem Jahr 1986. Mithilfe von Machine Learning-Techniken werden verschiedene Modelle entwickelt, um präzise Gehaltsvorhersagen zu ermöglichen.

## Daten

Der Datensatz stammt ursprünglich aus der StatLib-Bibliothek der Carnegie Mellon University und wurde 1988 in der Posterausstellung der ASA Graphics Section verwendet. Die Gehaltsdaten wurden aus der Sports Illustrated vom 20. April 1987 entnommen. Die Statistiken für 1986 sowie die Karrierestatistiken stammen aus dem 1987 Baseball Encyclopedia Update, veröffentlicht von Collier Books, Macmillan Publishing Company, New York.

### Variablen

- **AtBat**: Anzahl der Schlägerkontakte während der Saison 1986-1987
- **Hits**: Anzahl der Treffer während der Saison 1986-1987
- **HmRun**: Anzahl der Homeruns (vollständige Umrundung der Bases nach einem Schlag) während der Saison 1986-1987
- **Runs**: Anzahl der erzielten Runs (Punkte, die durch das Umrunden der Bases erzielt werden) während der Saison 1986-1987
- **RBI**: Anzahl der durch den Schlag erzielten Runs
- **Walks**: Anzahl der durch den Gegner verursachten Fehler
- **Years**: Spielzeit des Spielers in der Major League (Jahre)
- **CAtBat**: Anzahl der Schlägerkontakte während der gesamten Karriere
- **CHits**: Anzahl der Treffer während der gesamten Karriere
- **CHmRun**: Anzahl der Homeruns während der gesamten Karriere
- **CRuns**: Anzahl der erzielten Runs während der gesamten Karriere
- **CRBI**: Anzahl der durch den Schlag erzielten Runs während der gesamten Karriere
- **CWalks**: Anzahl der durch den Gegner verursachten Fehler während der gesamten Karriere
- **League**: Liga, in der der Spieler bis zum Saisonende gespielt hat (Faktor mit den Stufen A und N)
- **Division**: Position, in der der Spieler am Ende der Saison 1986 gespielt hat (Faktor mit den Stufen E und W)
- **PutOuts**: Anzahl der erzielten Outs (Ausschlüsse eines Gegners) im Spiel
- **Assists**: Anzahl der Assists während der Saison 1986-1987
- **Errors**: Anzahl der Fehler während der Saison 1986-1987
- **Salary**: Gehalt des Spielers in der Saison 1986-1987 (in Tausend)
- **NewLeague**: Liga, in der der Spieler zu Beginn der Saison 1987 gespielt hat (Faktor mit den Stufen A und N)

## Funktionen

1. **Datenvorverarbeitung**: 
   - **Fehlende Werte**: Identifikation und Behandlung von fehlenden Werten.
   - **Ausreißer**: Erkennung und Handhabung von Ausreißern.
   - **Feature Engineering**: Erstellung neuer Merkmale zur Verbesserung der Modellleistung.
   - **One-Hot Encoding**: Kodierung kategorialer Variablen.
   - **Feature Scaling**: Normalisierung der numerischen Merkmale.

2. **Explorative Datenanalyse (EDA)**:
   - Analyse der Verteilung und Beziehungen der Merkmale.
   - Untersuchung der Korrelationen zwischen den Variablen.
   - Visualisierung der wichtigsten Merkmale und Zielvariable.

3. **Modelltraining und -bewertung**:
   - Vergleich verschiedener Regressionsmodelle: Lineare Regression, Ridge, Lasso, ElasticNet, KNN, Entscheidungsbaum, Random Forest, Gradient Boosting, XGBoost, LightGBM und CatBoost.
   - Hyperparameter-Optimierung durch Grid Search.
   - Bewertung der Modelle anhand von RMSE und anderen Metriken.

4. **Feature Importance**:
   - Analyse der Wichtigkeit der Merkmale für die Vorhersage.

5. **Learning Curves**:
   - Untersuchung der Modellkomplexität durch Learning Curves.



