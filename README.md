# İMAJNest

**Son sürüm:** 2026.11.8.1256 (08.11.2026)

**[⬇ İMAJNest'i indir](https://github.com/AliYldz01/imajnest-kurulum/releases/latest/download/IMAJNest_Kurulum.exe)** · [İndirme sayfası](https://aliyldz01.github.io/imajnest-kurulum/)

Windows 10/11 (64 bit). Kurulum imzasız olduğu için Windows "bilgisayarınızı korudu" uyarısı gösterebilir: **Ek bilgi → Yine de çalıştır**. Uygulama lisans anahtarı ile çalışır.

## Deneme sürümü ve lisans

Ücretsiz deneme süresi talep etmek, lisans satın almak veya fiyat bilgisi almak için **Murat Yıldız** ile iletişime geçin: **[0532 574 04 33](tel:+905325740433)** (telefon) · **[WhatsApp](https://wa.me/905325740433)**

## Bu sürümde

- Lazer kesim yolu sacta her zaman görünür: giriş / çıkış, mikro bağlantı, delme noktası, kesim yönü, boş hareket ve parça sıra numarası.
- Simülasyon girişten başlıyor; parçadan parçaya geçiş (boş hareket) de simüle ediliyor.
- Yeni "Hesapla" düğmesi: kesim yolu, süre, doluluk ve maliyet yeniden hesaplanır.
- Yeni "Parçayı düzenle" penceresi (sacta sağ tık veya parça listesinde çift tık): kontur seçip (sürükleyerek çoklu seçim) giriş / çıkış, mikro bağlantı ve kerf ayarı; "benzer şekillerin tümüne uygula".
- Nesting penceresinde "giriş / mikro bağlantı / kerf uygula" seçenekleri; değerler malzeme tablosunda her kalınlık için.
- Giriş / çıkış komşu parçaya ve sac kenarına olan mesafenin yarısını otomatik olarak geçmiyor; karşı duvara da yaklaşmıyor.
- Kerf, girişin geldiği tarafa uygulanıyor (içeriden girişte içe).
- Mikro bağlantı: "Bağlantı yerine giriş (lead) ekle" seçeneği (malzeme tablosu, Otomatik Microjoint ve Parçayı düzenle); CypCut ve Raytools çıktısına yazılıyor.
- Başlangıca konan mikro bağlantı girişe bitişik ve kesim yönünü bozmayacak tarafta; elle mikro bağlantıda köşe ve başlangıç noktası yakalanıyor.
- Kesim başlangıcı önizlemede, sacta, CypCut'ta ve Raytools'ta aynı noktada (döndürülmüş parçalar ve daire delikler dahil).
- Mikro bağlantıda yeniden delme varsayılan olarak kapalı (giriş verilen kalınlıklar hariç).
- CypCut çıktısı: giriş yerleri, kesim sırası ve kesim yönü programdaki gibi.
- Raytools çıktısı: giriş / çıkış, mikro bağlantı (ve sonrası giriş), kerf ve kesim sırası artık dosyaya yazılıyor.
- Yeni: Raytools katman ayarlarını içe aktar (.HSTool) — Diğer menüsünde, CypCut seçeneğinin altında.
- Kesim süresi hesabı yenilendi: gaz, delme kademeleri, mikro bağlantı, hızlanma, kafa kaldırma ve başlangıca dönüş; özet satırında süre dökümü.
- Kesim sırası yeniden yazıldı: gerçek giriş / çıkış noktalarına göre en kısa yol, bölgesel "küçük parçalar önce", kesilmiş parçaların üzerinden geçmeme, delik sırası dış konturun girişine göre.
- Yeni sıra ayarları: başlangıç köşesi, delikleri art arda yakın kesmeme (kalın sac). Giriş yeri için "kafanın geldiği yöne en yakın kenar" seçeneği.
- Elle kesim sırası: Enter veya sağ tık ile bitir; seçilmeyen parçalar otomatik sıralanır.
- Sonuç sekmesinde "Seçili parçalarla boşlukları doldur"; parça listesinde seçim kutusu ve "istenen / yerleşmeyen" adet gösterimi (tek tıkla adet yazma).
- Parça ayar çubuğu taşınabilir; araç çubuğu Nesting Başlat düğmesinin altında.
- Çeşitli düzeltmeler ve hızlandırmalar.
