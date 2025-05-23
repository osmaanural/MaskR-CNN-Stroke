# MaskR-CNN-Stroke
🧠 Mask R-CNN ile Beyin İnmesinin Otomatik Segmentasyonu!

İnme, beyin damarlarında tıkanma veya kanama sonucu meydana gelen ve bireyin yaşam kalitesini doğrudan etkileyen ciddi bir nörolojik hastalıktır. Erken tanı ve doğru müdahale, hastanın yaşamını kurtarabilecek kadar kritiktir.

📌 Bu çalışmada, inme bölgelerinin otomatik olarak tespit edilmesi hedeflenmiştir. Derin öğrenme tabanlı Mask R-CNN modeli ile iskemik ve hemorajik inmelerin segmentasyonu gerçekleştirilmiştir.

📊 Kullanılan Modeller:

ResNet50

ResNet101

🔍 Veri Seti: Çalışmada, T.C. Sağlık Bakanlığı tarafından paylaşılan ve uzman radyologlarca etiketlenmiş beyin BT görüntülerinden oluşan kamuya açık bir veri seti kullanılmıştır.

📈 Değerlendirme Metrikleri:

IoU (Intersection over Union)

F1 Skoru

🏆 En Başarılı Sonuç: Veri artırma yapılmadan eğitilen ResNet101 modeli, segmentasyon performansında en yüksek başarıyı göstermiştir:

IoU: 0.9599

F1 Skoru: 0.9255

💡 Sonuç: Bu çalışma, yapay zekâ tabanlı sistemlerin, inme tanısında doğru ve hızlı sonuçlar sağlayarak klinik karar süreçlerine önemli katkılar sunabileceğini ortaya koymaktadır.
