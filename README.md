# depo1
📘 Proje Tanımı

Bu proje, bir yatırımın riskine göre performansını değerlendiren Sharpe oranını hesaplamak için tasarlanmış basit bir C programıdır.
Sharpe oranı, yatırımın beklenen getirisi ile risksiz faiz oranı arasındaki farkın, yatırımın riskine (standart sapma) bölünmesiyle elde edilir.
Bu metrik, yatırımın risk başına ne kadar getiri sağladığını gösterir ve finansal analizlerde yaygın olarak kullanılır.

⚙️ Kullanılan Teknolojiler

Programlama dili: C
Derleyici önerisi: Dev-C++ veya GCC

🧮 Hesaplama Formülü
Sharpe Oranı = (Yatırım Getirisi − Risksiz Getiri) / Standart Sapma​

💡 Girdi Bilgileri

Program çalıştığında kullanıcıdan aşağıdaki üç değer alınır:

Girdi	Açıklama	Örnek Değer
Beklenen Getiri	Yatırımın ortalama yıllık getirisi	0.15
Risksiz Getiri	Devlet tahvili gibi risksiz yatırımın oranı	0.05
Standart Sapma	Yatırımın risk düzeyi (getirilerdeki oynaklık)	0.12
📈 Çıktı Bilgileri

Program, kullanıcıdan alınan değerlerle Sharpe oranını hesaplar ve sonucu yorumlar.
Sonuç çıktısında:

Sharpe oranı değeri,

Risk-getiri dengesi hakkındaki yorum gösterilir.

💬 Yorumlama Tablosu
Sharpe Oranı Değeri	Yorum
< 1.0	Düşük — Yatırımın riskine göre getirisi zayıf.
1.0 – 2.0	İyi — Yatırım mantıklı olabilir.
2.0 – 3.0	Çok iyi — Risk başına yüksek getiri.
> 3.0	Mükemmel — Olağanüstü performans.

🚀 Programın Çalıştırılması

Dosyayı sharpe_orani.c adıyla kaydedin.
C derleyicinizde açın (örneğin Dev-C++).
Derleyip çalıştırın.
Ekrandaki yönlendirmelere göre verileri girin.
Hesaplanan Sharpe oranı ve değerlendirmesini görün.

📚 Ek Bilgi

Sharpe oranı, yatırım portföylerinin performansını karşılaştırmak için en yaygın kullanılan risk ayarlı ölçüttür.
Daha yüksek bir Sharpe oranı, yatırımın risk başına daha iyi getiri sağladığı anlamına gelir.
Finansal analizlerde portföy seçimi, fon karşılaştırması ve performans ölçümü için önemli bir göstergedir.
