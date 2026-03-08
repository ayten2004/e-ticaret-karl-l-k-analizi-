# E-Ticaret Karlılık Analizi ve OLS Regresyon Modeli
Bu projede, bir e-ticaret platformunun satış verilerini inceleyerek karlılığı etkileyen temel faktörleri bulmaya çalıştım. Temel amacım, sadece kod yazmak değil, veriler üzerinden şirketin özellikle indirim politikalarına dair işe yarar sonuçlar çıkarmaktı.
## Kullanılan Araçlar
- Python (Pandas, Statsmodels, Matplotlib, Seaborn)
## Analiz Adımları ve Metodoloji
İlk olarak modelin kafasının karışmaması için değişkenler arasında çoklu bağlantı (multicollinearity) olup olmadığına VIF (Variance Inflation Factor) testi ile baktım. `Sales` (3.15) ve `Shipping_Cost` (2.96) dahil tüm değerler sınırın çok altında ve temiz çıktığı için doğrudan OLS (Çoklu Doğrusal Regresyon) modelimi kurdum.
## Elde Ettiğim Sonuçlar
1. **İndirimlerin Negatif Etkisi:** Modeldeki en çarpıcı detay indirim (Discount) oranının kârlılık üzerindeki etkisiydi. Katsayı -222 (p=0.000) geldi. Veriyi grafiğe döktüğümde de yüksek indirimlerin kârı doğrudan sıfırın altına, yani zarara çektiğini net bir şekilde gördüm.
2. **Kategori Lideri:** Kategorilere göre ortalama kârlılığa baktığımda "Teknoloji" ürünlerinin diğer tüm kategorileri geride bıraktığını tespit ettim.
3. **Model Açıklayıcılığı:** R-squared değerim 0.319 çıktı. Yani sadece elimdeki 4-5 satış metriğiyle kârlılıktaki değişimin yaklaşık %32'sini istatistiksel olarak açıklayabiliyorum.
## Stratejik Çıkarım
Ortaya çıkan tabloya göre; şirketin pazar payı kapmak veya satış hacmini artırmak için uyguladığı kontrolsüz indirimler aslında ciddi zarar yazıyor. İndirimleri kısmak ve kâr marjı zaten yüksek olan teknoloji kategorisine odaklanmak veriye dayalı en mantıklı strateji olarak görünüyor.
## Geliştirici Hakkında
**[Cansu Ayten]**
- Necmettin Erbakan Üniversitesi / İstatistik (3. Sınıf)
- **İlgilendiğim Alanlar:** Veri Analizi, İstatistiksel Modelleme, Siber Güvenlik ve Ağ Teknolojileri
- **Kullandığım Araçlar:** Python, R, MATLAB,SPSS,EXCEL
- [www.linkedin.com/in/cansu-ayten-002a57299] | [https://githup.com/ayten2004]
