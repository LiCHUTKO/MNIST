# MNIST 🖼️

## Opis projektu 📚
Ten projekt demonstruje, jak zbudować, trenować i oceniać model sieci neuronowej do rozpoznawania ręcznie pisanych cyfr z użyciem zbioru danych MNIST. Wykorzystujemy biblioteki TensorFlow, Keras, Matplotlib, NumPy oraz PIL.

## Struktura projektu 📂
- `notebook.ipynb`: Jupyter Notebook zawierający cały kod do załadowania danych, budowy modelu, trenowania, oceny oraz predykcji.

## Wymagania 📦
- Python 3.x
- TensorFlow
- Keras
- Matplotlib
- NumPy
- PIL

## Instalacja 🔧
Aby zainstalować wymagane biblioteki, uruchom poniższe polecenie:
```bash
pip install tensorflow matplotlib numpy pillow
```

## Uruchomienie projektu ▶️
1. Otwórz `notebook.ipynb` w Jupyter Notebook lub Jupyter Lab.
2. Uruchom wszystkie komórki, aby załadować dane, zbudować model, przeprowadzić trening, ocenić model oraz dokonać predykcji.

## Opis notebooka 📓
- **Załadowanie potrzebnych bibliotek**: Importowanie wszystkich niezbędnych bibliotek.
- **Załadowanie i normalizacja danych**: Ładowanie zbioru danych MNIST i normalizacja wartości pikseli.
- **Tworzenie modelu**: Budowa modelu sieci neuronowej z użyciem Sequential API z Keras.
- **Kompilacja i trenowanie**: Kompilacja modelu i trenowanie na danych treningowych.
- **Testowanie i wyniki**: Ocena modelu na zbiorze testowym.
- **Predykcja z wizualizacją**: Dokonanie predykcji na kilku przykładach z zestawu testowego i wizualizacja wyników.
- **Własny przykład liczby**: Ładowanie własnego obrazu liczby i dokonanie predykcji za pomocą modelu.

## Autor ✍️
LiCHUTKO