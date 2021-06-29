# Implementacija-strategije-za-zajem-dividend
Izvorna koda in testni podatki za vrednotenje strategije za zajem dividend

## a) Opis datotek

1. *All simbols.txt* <br/>
Datoteka vsebuje seznam vseh simbolov Ameriških podjetij, ki smo jih upoštevali pri analizi.

2. *All data for dividend capture strategy.txt* <br/>
Datoteka vsebuje podatke vseh instanc izvedbe strategije za zajem dividend za podjetja, ki so v seznamu All simbols.txt od 2011-06-01 do 2020-12-10. Stolpce predstavljajo naslednji atributi:
- simbol - simbol podjetja.
- p_dec - Procent dobička, pri izvedbi strategije za zajem dividend, ob nakupu na datum izjave in prodaje na datum prejšnje dividende.
- p_bef_ex - Procent dobička, pri izvedbi strategije za zajem dividend, ob nakupu na dan pred datumom prejšnje dividende in prodaje na datum prejšnje dividende.
- p_best - Procent dobička, pri izvedbi strategije za zajem dividend, ob najboljšem možnem nakupu finančnega inštrumenta med datumom izjave in datumom prejšnje dividende in prodaje na datum prejšnje dividende.
- dec_d - datum izjave.
- ex_d - datum prejšne dividende.
- rec_d - datum zapisa.
- pay_d - datum plačila dividend.
- dividend - vrednost dividende.
- b_day_to_buy - datum najbolšega nakupa za izračun p_best.
- b_price_to_buy - vrednost delnice podjetja ob nakupu.
- price_on_ex_day_open - vrednost delnice podjetja ob prodaji na datum prejšne dividende.
- stock_price_on_dec_date - vrednost delnice podjetja na datum izjave.
- stock_price_before_ex_date1 -vrednost delnice podjetja na dan pred datumom prejšne dividende.
- proc_best_buy - p_best.
- proc_dec_buy - p_dec.
- proc_bef_ex_buy - p_bef_ex.
 
3. *BTC.csv* <br/>
Pridobljeno iz: https://www.kaggle.com/mczielinski/bitcoin-historical-data
Datoteka vsebuje podatke za Bitcoin od 17.09.2014 do 08.05.2021.
Opis stolpcev:
- 1)Datum
- 2)Open
- 3)High
- 4)Low
- 5)Close
- 6)Adj close
- 7)Volume

4. *SP500.csv* <br/>
Pridobljeno iz https://www.kaggle.com/camnugent/sandp500
Datoteka vsebuje podatke za S&P 500 od 31.12.2021 do 07.05.2021.
Opis stolpcev:
- 1)Datum
- 2)Open
- 3)High
- 4)Low
- 5)Close
- 6)Adj close
- 7)Volume

5. *GOOGL.txt* <br/>
Podatki gibanja vrednosti delnice za podjetje Google, od  04.01.2010 do 17.05.2021, ki smo jih pridobili iz knjižnice Pandas Datareader.
Opis stolpcev:
- 1) Id vrstice
- 2) Datum 
- 3) Vrednost kapitala


6. *AMZN.txt* <br/>
Podatki gibanja vrednosti delnice za podjetje Amazon, od 04.01.2010 do 17.05.2021, ki smo jih pridobili iz knjižnice Pandas Datareader.
Opis stolpcev:
- 1) Id vrstice
- 2) Datum 
- 3) Vrednost kapitala


7. *StrategyRegularExampleStepByStep.html* <br/>
Datoteka vsebuje step-by-step kako smo izvajali strategijo za zajem dividend.
Prikazani so vsi rezultati pri pridobivanju podatkov iz  baze in prav tako vse akcije strategije za vsako leto posebaj. Vsebovan je tudi grafični prikaz 
gibanja kapitala.
Datoteko lokalno prenesite in jo odprite v html foramtu.

8. *CompareDividendStrategyWithOthersAlternatives.html](https://andrejmohoric.github.io/CompareDividendStrategyWithOthersAlternatives/)* <br/>
Datoteka vsebuje step-by-step kako smo primerjali strategijo za zajem dividend z drugimi finančnimi inštrumenti.
Prikazani so vsi rezultati. 
Datoteko lokalno prenesite in jo odprite v html foramtu.

