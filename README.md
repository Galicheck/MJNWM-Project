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

Zbiór danych zawiera następujące 16 kolumn:
- **Date**: data,
- **AMZN_Open**: cena, po której akcje Amazon.com były notowane po raz pierwszy po otwarciu rynku (w USD),
- **AMZN_High**: najwyższa cena akcji Amazon.com w dniu handlowym (w USD),
- **AMZN_Low**: najniższa cena akcji Amazon.com w dniu handlowym (w USD),
- **AMZN_Close**: ostatnia cena akcji Amazon.com po zamknięciu rynku (w USD),
- **AMZN_Volume**: całkowita liczba akcji Amazon.com będących w obrocie w ciągu dnia handlowego (w USD),
- **sp100_Open**: zbiorczy punkt startu akcji indeksu S&P 100 (w USD),
- **sp100_High**: szczytowy poziom wyników indeksu S&P 100 w trakcie sesji giełdowej (w USD),
- **sp100_Low**: najniższy punkt notowań indeksu S&P 100 podczas sesji giełdowej (w USD),
- **sp100_Close**: zbiorczy punkt końcowy akcji indeksu S&P 100 (w USD),
- **sp100_Volume**: ogólny poziom aktywności i zainteresowania obrotem akcjami wchodzącymi w skład indeksu S&P 100 (w USD),
- **Inflation_USA**: średnia roczna stopa inflacji w USA (w %),
- **Inflation_UE**: średnia roczna stopa inflacji w Unii Europejskiej (w %),
- **Inflation_World**: średnia roczna stopa inflacji na świecie (w %),
- **Revenue_Billions**: przychody Amazon.com (w miliardach USD).

## Jak uruchomić ten projekt

Po sklonowaniu repozytorium uruchom plik Project_AMZN_prediction.ipynb w Jupyter Notebook.
