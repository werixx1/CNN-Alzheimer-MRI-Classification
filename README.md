## Wnioski z raportów:
Najlepsze wyniki (wysoka dokładność i sprawność na danych walidacyjnych i treningowych) osiągały modele trenowane **z użyciem** (przy 10 epokach):
- akcelatora GPU,
- po augmentacji danych,
- po normalizacji danych
- przy rozmiarach zdjęć 224x224
- na strukturze ResNet50 i MobileNet
- batch size = 32
- ilości próbek 9940

Analizując wykresy Training and Validation Accuracy i Training and Validation Loss można wysunąć wniosek, aby w kolejnych modelach zastosować early stopping,
ponieważ często w okolicach końcowych epok następowało przeuczanie się. Dodatkowo zastowowanie takich metod optymalizacji jak Dropout, albo większy batch size 
pograszało wyniki modelu, z czego można wnioskować, że na takim zbiorze danych, jaki został użyty do treningu lepiej sprawują się prostsze modele. \
<br>
[Tutaj] znajdują się dwa nowe modele, w których zastosowałam sugestie wyciągnięte z raportów:)
