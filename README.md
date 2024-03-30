# Zastosowanie metod Machine Learning w przewidywaniu cen akcji firmy Amazon.com

Celem projektu jest zbudowanie kilku modeli predykcyjnych oraz porównanie ich skuteczności i poprawności w przewidywaniu cen akcji Amazon.com.

Do predykcji wykorzystamy między innymi:
- regresję liniową,
- SVM (maszyny wektorów nośnych),
- regresję Random Forest,
- regresor wzmacniający gradient,
- LSTM (pamięć długo-krótkoterminową),
- GRU (bramkowane jednostki cykliczne),
- CNN (konwolucyjną sieć neuronową),
- ARIMA (zintegrowaną średnią ruchomą autoregresyjną).

Następnie spróbujemy wyłonić najlepszy model i zastosować go do danych czasu rzeczywistego (styczeń-maj 2024).

## Autorzy projektu

**Koordynator projektu**
- Natalia Szczepkowska

**Pozostali współautorzy**
- Jakub Galikowski
- Magdalena Lamczyk
- Wiktoria Sarabon
- Martyna Szawłowska

## Informacje o zbiorze danych

Zbiór danych `final_data.csv` zawiera następujące 20 kolumn:
- **Date**: Data,
- **AMZN_Open**: Cena, po której akcje Amazon.com były notowane po raz pierwszy po otwarciu rynku (w USD),
- **AMZN_High**: Najwyższa cena, po której notowano akcje Amazon.com w dniu handlowym (w USD),
- **AMZN_Low**: Najniższa cena, po której notowano akcje Amazon.com w dniu handlowym (w USD),
- **AMZN_Close**: Cena, po której ostatnio notowano akcje Amazon.com po zamknięciu rynku (w USD),
- **AMZN_Volume**: Całkowita liczba akcji Amazon.com będących w obrocie w ciągu dnia handlowego (w USD),
- **SP100_Open**: Zbiorczy punkt startu akcji indeksu S&P 100 (w USD),
- **SP100_High**: Szczytowy poziom notowań indeksu S&P 100 w trakcie sesji giełdowej (w USD),
- **SP100_Low**: Najniższy punkt notowań indeksu S&P 100 podczas sesji giełdowej (w USD),
- **SP100_Close**: Zbiorczy punkt końcowy akcji indeksu S&P 100 (w USD),
- **SP100_Volume**: Ogólny poziom aktywności i zainteresowania obrotem akcjami wchodzącymi w skład indeksu S&P 100 (w USD),
- **Inflation_USA**: Średnia roczna stopa inflacji w USA (w %),
- **Inflation_UE**: Średnioroczna stopa inflacji w Unii Europejskiej (w %),
- **Inflation_World**: Średnia roczna stopa inflacji na świecie (w %),
- **Revenue_Billions**: Przychody Amazon.com (w miliardach USD),
- **GCD**: Produkt Krajowy Brutto (w miliardach USD),
- **CCI Total**: Wskaźnik pewności konsumenta ogółem (powyżej 100 – konsumenci są skłonni do przyszłych wydatków/zakupów; poniżej 100 – konsumenci ograniczą swoje wydatki),
- **CCI USA**: Wskaźnik pewności konsumenta w USA,
- **CCI Europe**: Wskaźnik pewności konsumenta w Europie,
- **Unemployment_USA**: Stopa bezrobocia w USA (w %).

## Jak uruchomić ten projekt

Po sklonowaniu repozytorium skonfiguruj środowisko wirtualne i zainstaluj niezbędne wymagania:
```
python -m venv venv 
venv\Scripts\activate
pip install -r requirements.txt
```

Następnie uruchom Jupyter Notebook wpisując:
```
jupyter notebook
```

Otwórz i uruchom plik `project_AMZN_prediction.ipynb`.


