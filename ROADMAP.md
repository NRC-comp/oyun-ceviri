
```mermaid
%% Example with selection of syntaxes
        gantt
        dateFormat  DD-MM-YYYY
        title Oyun çevirisi yol haritası

        section Dokümentasyon
        Ana sayfanın tamamlanması                          :active, a1, 18-03-2026, 30-03-2026
        Bazı terimlerin Türkçeleştirilmesi                 :active, term1,28-03-2026, 20h
        Genel-geçer Oyun Motoru formatlarının yazılması    :active, doc1, after a1 , 48h

        section Hackleme
        TP Metinlerin yerelleştirme platformuna aktarılması               :active, a1, after doc1, 3d

        section Çeviri
        TP çeviri :30d 
```
