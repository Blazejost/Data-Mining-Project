# Przewodnik po Dokumentacji Projektu Data Mining

## 📄 Plik Dokumentacji

**Nazwa pliku:** `Dokumentacja_Projekt_Data_Mining.ipynb`

## 🎯 Cel

Kompletna dokumentacja projektu Data Mining zawierająca:
- Analizę danych transakcyjnych sklepu internetowego
- Implementację 4 metod eksploracji danych (PCA, K-Means, Apriori, Random Forest)
- Wyniki, wizualizacje i wnioski

## 📋 Wymagane Informacje do Uzupełnienia

Przed użyciem dokumentacji, **uzupełnij następujące placeholdery** w pierwszej sekcji (strona tytułowa):

- `[IMIĘ I NAZWISKO]` - Twoje imię i nazwisko
- `[GRUPA]` - Numer grupy
- `[STOPIEŃ STUDIÓW]` - np. "Studia II stopnia" lub "Studia I stopnia"
- `[SEMESTR]` - np. "Semestr zimowy 2023/2024"
- `[WYDZIAŁ]` - Nazwa wydziału, np. "Wydział Informatyki"
- `[NAZWA UCZELNI]` - Pełna nazwa uczelni

## 🚀 Jak Otworzyć i Użyć

### Opcja 1: Jupyter Notebook
```bash
jupyter notebook Dokumentacja_Projekt_Data_Mining.ipynb
```

### Opcja 2: JupyterLab
```bash
jupyter lab Dokumentacja_Projekt_Data_Mining.ipynb
```

### Opcja 3: VS Code
1. Zainstaluj rozszerzenie "Jupyter" w VS Code
2. Otwórz plik `.ipynb`
3. Możesz przeglądać i wykonywać komórki

### Opcja 4: Google Colab
1. Wejdź na [colab.research.google.com](https://colab.research.google.com)
2. File → Upload notebook
3. Wybierz `Dokumentacja_Projekt_Data_Mining.ipynb`

## 📚 Struktura Dokumentacji

Dokumentacja zawiera **9 głównych sekcji**:

1. **Strona tytułowa** - Metadane projektu
2. **Spis treści** - Nawigacja z linkami
3. **Wstęp i Cel Projektu** - Wprowadzenie i cele
4. **Opis Zbioru Danych** - UCI Online Retail Dataset
5. **Opis Zastosowanych Metod** - Teoria PCA, K-Means, Apriori, Random Forest
6. **Implementacja** - Kod, biblioteki, algorytmy
7. **Wyniki** - Wyniki numeryczne i graficzne
8. **Interpretacja i Wnioski** - Analiza wyników
9. **Podsumowanie** - Wnioski końcowe

## 💻 Wymagania Techniczne

### Wymagane biblioteki Python:
```
pandas >= 3.0.0
matplotlib >= 3.10.8
seaborn >= 0.13.2
scikit-learn >= 1.8.0
mlxtend >= 0.24.0
numpy
```

### Instalacja:
```bash
# Z użyciem pip
pip install pandas matplotlib seaborn scikit-learn mlxtend numpy

# LUB z użyciem uv (jak w projekcie)
uv sync
```

## 📊 Zawartość

- **20 komórek Markdown** - Opisy, wyjaśnienia, teoria
- **25 komórek Code** - Kod Python z implementacjami
- **Wszystkie wizualizacje** - Wykresy z obu notebooków źródłowych
- **Język:** Polski

## ✅ Co Jest Zawarte

✅ Kompletna analiza eksploracyjna (EDA)  
✅ Analiza RFM (Recency, Frequency, Monetary)  
✅ Market Basket Analysis z algorytmem Apriori  
✅ Segmentacja klientów (K-Means clustering)  
✅ Klasyfikacja (Random Forest)  
✅ Redukcja wymiarowości (PCA)  
✅ Wizualizacje i wykresy  
✅ Interpretacje wyników  
✅ Wnioski biznesowe  

## �� Wykonywanie Kodu

Aby wykonać całą dokumentację:

1. Otwórz notebook w Jupyter
2. Upewnij się, że plik `OnlineRetail.csv` jest w tym samym katalogu
3. Wybierz **Cell → Run All** lub **Kernel → Restart & Run All**
4. Poczekaj na zakończenie obliczeń (może potrwać kilka minut)

## 📝 Eksport

### Do PDF:
```bash
jupyter nbconvert --to pdf Dokumentacja_Projekt_Data_Mining.ipynb
```

### Do HTML:
```bash
jupyter nbconvert --to html Dokumentacja_Projekt_Data_Mining.ipynb
```

## 🎓 Uwagi dla Studentów

- Dokumentacja zawiera **wszystkie wymagane sekcje** zgodnie z wytycznymi projektu
- Kod jest **skopiowany i zintegrowany** z `eda.ipynb` i `analiza_rfm.ipynb`
- Przed oddaniem projektu **uzupełnij wszystkie placeholdery**
- Możesz modyfikować treść zgodnie z własnymi potrzebami
- Upewnij się, że wszystkie komórki wykonują się bez błędów

## ❓ Pytania i Problemy

Jeśli napotkasz problemy:
1. Sprawdź czy wszystkie biblioteki są zainstalowane
2. Upewnij się, że `OnlineRetail.csv` jest dostępny
3. Sprawdź wersję Python (wymagane 3.12+)
4. Przeczytaj komunikaty błędów w notebook

## 📧 Kontakt

W razie problemów, sprawdź dokumentację bibliotek:
- [Pandas](https://pandas.pydata.org/)
- [Scikit-learn](https://scikit-learn.org/)
- [MLxtend](http://rasbt.github.io/mlxtend/)

---

**Powodzenia z projektem! 🚀**
