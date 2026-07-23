# Klasifikacija tekstualnih podataka - Farm Ads dataset

Projekat se bavi klasifikacijom tekstualnih podataka korišćenjem Farm Ads skupa podataka. 
Cilj projekta je poređenje različitih klasifikacionih algoritama i analiza uticaja redukcije dimenzionalnosti nad TF-IDF reprezentacijom podataka.

U okviru projekta izvršeno je:
- preprocesiranje tekstualnih podataka,
- formiranje TF-IDF reprezentacije,
- redukcija dimenzionalnosti primenom χ² selekcije atributa i TruncatedSVD metode,
- treniranje i evaluacija više klasifikacionih modela:
  - Multinomial Naive Bayes,
  - LinearSVC,
  - KNN,
  - Decision Tree,
  - Logistic Regression.

Performanse modela poređene su korišćenjem Accuracy, Precision, Recall i F1-score metrika, kao i ROC/AUC analize. 
Najbolje rezultate ostvario je LinearSVC model nakon χ² selekcije atributa.