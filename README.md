# Napełnianie KEG

Projektowanie i modelowanie układu sekwencyjnego sterowania procesem produkcyjnym

System napełniania beczek typu KEG składa się z dwóch maszyn połączonych szeregowo  (rys. 1) - myjki beczek (maszyna M1) oraz napełniarki beczek (maszyna M2). Obie maszyny nie posiadają bufora (miejsca oczekiwania produktu). Beczki transportowane są za pomocą przenośnika taśmowego. Proces wygląda następująco: jeśli beczka przyjeżdża i maszyna M1
jest zajęta, beczka jest usuwana z kolejki, Jeśli maszyna M1 kończy proces i maszyna M2 jest zajęta, M1 przetrzymuje beczkę do momentu ukończenia procesu przez M2 (blokada beczki). Częstotliwość podawania beczek przez podajnik jest równa 1min. Dla wyżej opisanego procesu opracuj graf automatu stanów w postaci (Q, X, Y, δ, λ) i zamodeluj go w przyborniku StateFlow środowiska Matlab/Simulink z użyciem automatu Moore'a, Mealy'ego oraz klasycznego diagramu StateFlow, zakładając, że obie maszyny są na początku puste (bezczynne). Przeprowadź badania symulacyjne i porównaj działanie układu w zależności od
rodzaju automatu.

