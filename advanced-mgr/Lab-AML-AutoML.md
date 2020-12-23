# Laboratorium `Azure Machine Learning - Automated (Auto) ML` na Microsoft Azure



## Repo

- nazwa repozytorium ma zawierać prefix/przedrostek `AI-on-Microsoft-Azure`, czyli może być np.  `AI-on-Microsoft-Azure-2020` ,  `AI-on-Microsoft-Azure-PW` albo po prostu  `AI-on-Microsoft-Azure` 
- repozytorium na GitHub/GitLab/BitBucket - gdzie Wam wygodniej
- sprawozdanie/raport w formie pliku **.ipynb** 



## Część praktyczna

- Sprawozdanie/raport zawierające (1 plik) - **.ipynb** (Jupyter Notebook) 
  - scenariusz / use case dla którego realizowaliście eksperyment (na podstawie danych, określacie jaki task (classification, regression czy time series), jaka kolumna i dlaczego będzie przewidywana)
  - wykonane przez Was kroki do zbudowania takiego eksperymentu
  - kod + dane (link) niezbędne do zreprodukowania Waszego rozwiązania - *Czyli piszecie w notebooku kod eksperymentu i go komentujecie - albo w kodzie albo poprzez dodanie wstawek w Markdown*
  - Skąd wziąć dane? 
    - COVID: [Coronavirus (COVID-19) Cases - Our World in Data](https://ourworldindata.org/covid-cases)
    - kaggle.com
    - dowolne miejsce z publicznie dostępnym datasetem (excel, csv). **Inne pomysły na use case mile widziane**. 
  - Mam dane, co dalej?
    - tworzymy eksperyment z użyciem Auto-ML
      - pierwszy krok, to przeklikać i zrozumieć jak Auto ML działa z UI
      - drugi krok - stworzenie eksperymentu, przy użyciu auto-ml i danych przez Was wybranych w jupyternotebook
        - inspirować można się: [azureml-workshop-2020/binayclassification-employee-attrition-autoaml-remote-amlcompute.ipynb at master · csiebler/azureml-workshop-2020 (github.com)](https://github.com/csiebler/azureml-workshop-2020/blob/master/2-training-inference/2.3-automl-training/remote-compute/binayclassification-employee-attrition-autoaml-remote-amlcompute.ipynb) i innymi publicznie dostępnymi notebookami
        - celem eksperymentu jest użycie Auto-ML, który dla zdefiniowanego zadania (classification, regression, time series) ucuhomi dostępne modele i określi ich skuteczność. 
        - kolejno naszym zadaniem jest określenie najlepszego (najskuteczniejszego) modelu - i wyliczenie skuteczności tego modelu na danych testowych
        - kolejno komentujemy krok po kroku, opisując co się wykonało w naszym notebooku. Tutaj ważne - tworząc opisy proszę myśleć o dwóch osobach, które ten notebook będą czytały:
          - pierwsza osoba to stereotypowy człowiek z najwyższego biznesu (CEO), który o Data Science słyszał coś na konferencji w Nowym Jorku i myśli, że to całe AI jest bardzo proste bo już od lat 70 przecież wszystkim znane, jest wszędzie (bo auta autonomiczne, samoloty, roboty, IoT) i skuteczność AI to 100%. Nasz CEO chce zabłysnąć wiedzą przed współpracownikami i i przez 5minut będzie opowiadał o tym, jak to w Azure jest automatyczny machine learning - czyli automatyczna sztuczna inteligencja. Wiedza CEO będzie oparta jedynie o wasze sprawozdanie. 
          - druga osoba to świeży inż. mgr Programista ze specjalizacją i hands-on w Data Science. Nasz absolwent nie zna chmury, nie zna Azure i nie wie co to auto-ml robi, jak to uruchomić, jakie parametry przekazać. Ale za to jest światły i jest ninja w programowaniu. Pan Programista dostał zadanie w nowej pracy - demo Automated ML w AML przed całym technicznym zespołem. Pan Programista wybiera właśnie wasze sprawozdanie do przygotowania się do tego dema i będzie właśnie wasze rozwiązanie reprodukował. 



## Deadlines - jeden

- 27.01 - 10:00 - link do formularza, przez który zgłaszacie zrealizowanie tego zadania laboratorium: https://bit.ly/37hMKPX 
