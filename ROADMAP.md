
```mermaid
%% Example with selection of syntaxes
        gantt
        dateFormat  DD-MM-YYYY
        title Oyun çevirisi yol haritası

        section Dokümentasyon
        Ana sayfanın tamamlanması                          :active, a1, 18-03-2026, 01-04-2026
        Bazı terimlerin Türkçeleştirilmesi                 :term1, 28-03-2026, 3d
        Unity ve Unreal formatlarının yazılması    :doc1, 28-03-2026, 4d

        section Hackleme
        TP Metinlerin yerelleştirme platformuna aktarılması               : a1, after doc1, 3d
        TP çeviri kılavuzunun hazırlanması                                : h2, after a1, 5d

        section Çeviri
        TP çeviri :50d 
```
