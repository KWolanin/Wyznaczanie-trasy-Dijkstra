# Wyznaczanie najtańszego kursu lotniczego między stolicami europejskimi za pomocą algorytmu Dijkstry

## Opis projektu
Projekt wykonany w języku Python na potrzeby zaliczenia przedmiotu teoria grafów. Projekt ma na celu wyznaczenie natańszej trasy lotniczej pomiędzy wybranymi miastami-stolicami. Obejmuje graf przedstawiający wzajemne położenie lotnisk stolic europejskich (poszczególne wierzchołki noszą nazwy stolic, z wyjątkiem stolicy Malty - tu użyto nazwy wyspy z powodu, że to jej nazwę nosi lotnisko). Graf opiera się na współrzędnych geograficznych, łączy 44 miasta, z których kilka nie posiada lotnisk (np. Berno), oraz składa się z 386 możliwych połączeń lotniczych. Oprócz grafu w skład projektu wchodzi algorytm, który oblicza najkorzystniejszą cenowo trasę pomiędzy dwoma miastami, informuje o cenie, ilości lotów i, w razie potrzeby, wskazuje kwotę połączenia bezpośredniego (o ile jest droższe niż wytyczone przez algorytm). Dla zobrazowania wyniku stworzono dodatkowy graf wskazujący powstałą trasę.<br>
Dla uproszczenia grafu założono, że wszystkie miasta mają tylko po jednym lotnisku.

[Link do poglądu](https://nbviewer.jupyter.org/github/KWolanin/Grafy-Python/blob/master/Projekt%20zaliczeniowy%2C%20Katarzyna%20Wolanin%20%283%29.ipynb)
