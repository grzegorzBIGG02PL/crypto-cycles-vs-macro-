# crypto-cycles-vs-macro-

## Cel projektu
Celem projektu jest zbadanie przepływu kapitału w kryptowalutach (BTC → ETH → Altcoins) oraz jego zależności od globalnej koniunktury rynkowej.  
Projekt łączy analizę danych finansowych (crypto + rynki tradycyjne + dane makro) z wizualizacjami w Tableau.

## 🔍 Kluczowe pytania badawcze
1. Jak wygląda dominacja BTC/ETH/Altcoins w różnych fazach rynku?
2. Czy kapitał faktycznie przepływa od BTC do ETH i dalej do altów w okresach hossy?
3. Jak cykle krypto korelują z rynkami tradycyjnymi (S&P500, Nasdaq, złoto, dolar)?
4. Jak decyzje FED (stopy procentowe) i dane makro wpływają na rynek krypto?

## 🗂️ Struktura repozytorium
- `R/` – skrypty R do pobierania danych i analizy
- `data/` – przykładowe dane (CSV)
- `SQL/` – (opcjonalnie) zapytania SQL do obróbki danych
- `tableau/` – zrzuty ekranów + link do dashboardu Tableau Public

## ⚙️ Źródła danych
- Binance API – ceny i wolumeny BTC, ETH, Altcoins  
- Yahoo Finance API – indeksy (S&P500, Nasdaq), złoto, dolar (DXY)  
- FRED (Federal Reserve Economic Data) – stopy procentowe, inflacja
- CoinGecko - dane dotyczące market cap - Crypto, Bitcoin, Etherum

## 📊 Analiza
- Dominacja BTC/ETH/Altcoins – udział w kapitalizacji/wolumenie  
- Rolling correlations – BTC vs ETH, BTC vs S&P500, BTC vs złoto  
- Event study – wpływ decyzji FED i dużych spadków/wzrostów na rynek krypto

## 📈 Wizualizacje (Tableau)

### Przykładowe wizualizacje:
- Dominacja BTC/ETH/Altcoins w czasie  
- Korelacje krypto vs tradycyjne rynki  
- Timeline eventów makro (np. decyzje FED)  

## ✅ Wnioski

## 🛠️ Technologie
- R – pobieranie danych, analiza statystyczna, obróbka  
- SQL – opcjonalnie do przechowywania i agregacji danych  
- Tableau Public – wizualizacja i dashboard  
- GitHub – repozytorium kodu i dokumentacji  


