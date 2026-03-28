
```mermaid
%% Example with selection of syntaxes
        gantt
        dateFormat  DD-MM-YYYY
        title Oyun çevirisi yol haritası

        section Dokümentasyon
        Ana sayfanın tamamlanması                          :active, a1, 18-03-2026, 30-03-2026
        Bazı terimlerin Türkçeleştirilmesi                 :term1, 28-03-2026, 40h
        Genel-geçer Oyun Motoru formatlarının yazılması    :doc1, 28-03-2026, 48h

        section Hackleme
        TP Metinlerin yerelleştirme platformuna aktarılması               : a1, after doc1, 3d

        section Çeviri
        TP çeviri :5d 
```
