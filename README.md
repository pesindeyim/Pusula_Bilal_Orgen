Yan Etki Analizi ve Veri Ön İşleme (Side Effect Analysis and Preprocessing)

**Ad Soyad:** Bilal Örgen  
**E-posta:** bilalorgen@example.com

**Proje Açıklaması**
Bu proje, ilaçların yan etkilerini analiz etmek ve eksik veri sorunlarını çözmek amacıyla yapılmıştır. 
Projede, yan etkilerin dağılımı incelenmiş, eksik veriler uygun yöntemlerle doldurulmuş ve bazı veri keşif analizleri gerçekleştirilmiştir.

Proje kapsamında aşağıdaki adımlar uygulanmıştır:
1. Eksik verilerin tespiti ve giderilmesi
2. Kategorik verilerin en sık görülen değerle doldurulması
3. Sayısal verilerin ortalama ile doldurulması
4. Verilerin görselleştirilmesi ve temel analizlerin yapılması

**İçindekiler**
- **Veri Seti**: Yan etki verisi, ilaç ve hastalarla ilgili çeşitli bilgileri içermektedir.
- **Veri Keşif Analizi (EDA)**: Verinin genel özelliklerinin anlaşılması ve görselleştirilmesi.
- **Veri Ön İşleme**: Eksik verilerin giderilmesi ve kategorik/sayısal verilerin işlenmesi.
- **Görselleştirme**: Yan etkiler, yaş ve kilo gibi özelliklerin dağılımı ve ilişkileri.

**Kullanılan Kütüphaneler**
Bu projede aşağıdaki Python kütüphaneleri kullanılmıştır:
- `pandas`: Veri manipülasyonu ve analiz için.
- `matplotlib`: Veri görselleştirme için.
- `seaborn`: Gelişmiş veri görselleştirme için.
- `scikit-learn`: Eksik veri doldurma işlemleri için.

**Kurulum**
Projeyi yerel ortamınızda çalıştırmak için aşağıdaki adımları izleyebilirsiniz:

1. Gerekli Python paketlerini yükleyin:
   ```bash
   pip install pandas matplotlib seaborn scikit-learn
   ```

2. Proje dosyasını klonlayın veya indirin:
   ```bash
   git clone https://github.com/bilalorgen/Pusula_Bilal_Orgen.git
   cd Pusula_Bilal_Orgen
   ```

3. Veriyi yükleyip, .csv formatında okuyarak analiz edebilirsiniz:
   ```python
   df = pd.read_csv('side_effect_data.csv')
   ```

**Projenin Çalıştırılması**
Projeyi çalıştırmak için, Jupyter Notebook veya bir Python IDE kullanabilirsiniz. Aşağıdaki adımlar projeyi çalıştırmanıza yardımcı olacaktır:

1. Kodları çalıştırmadan önce veri setini projeye ekleyin.
2. EDA ve veri ön işleme adımlarını sırasıyla çalıştırın.
3. Sonuçları grafikler ve özet tablolar aracılığıyla inceleyin.

**Veri Ön İşleme Adımları**
- **Eksik Verilerin Doldurulması**: Kategorik değişkenlerde en sık tekrar eden değerler, sayısal verilerde ise ortalama değerlerle doldurulmuştur.
- **Veri Dönüşümleri**: Doğum tarihi sütunu yaş hesaplaması için işlenmiştir.
- **Görselleştirme**: Yan etkilerin dağılımı ve yaş-kilo ilişkisi grafiklerle gösterilmiştir.

**Sonuç:**
Proje sonucunda, ilaç yan etkileri ve hastalarla ilgili bilgilerin temizlenmiş ve analiz edilmiş hali elde edilmiştir. 
Eksik veriler uygun yöntemlerle doldurulmuş ve görselleştirme ile yan etkilerin dağılımı incelenmiştir.
