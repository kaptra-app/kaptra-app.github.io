# Kaptra — Gizlilik Politikası

Son güncelleme: 24 Eylül 2026

Bu politika Kaptra'nın Android sürümünü kapsar.

## Kısaca

- Belgeleriniz telefonunuzda saklanır. Kaptra onları hiçbir yere
  göndermez, telefonunuzun Google yedeğine de koymaz. Tarama, metin tanıma
  ve PDF üretimi telefonunuzda yapılır.
- Sunucumuz, hesap sistemimiz ve bulutumuz yok. Biz, Kaptra'nın geliştiricisi
  olarak, sizden hiçbir veri almıyoruz: ne belgelerinizi ne de uygulamayı
  nasıl kullandığınızı.
- Reklam yok. Kaptra'ya analitik ya da izleme aracı eklenmedi.
- Kaptra'nın internet izni yok. Uygulamanın kendisi ağ bağlantısı açamaz.
- Tarayıcıyı ve satın almayı Google sağlar. Bu iki bileşenin Google'a ne
  gönderebileceği aşağıda ayrıca anlatılıyor.

## Belgeleriniz

Taradığınız sayfalar, bunlardan üretilen görseller, sayfalardan tanınan metin
ve belge adları telefonunuzda, Kaptra'ya ayrılmış depolama alanında durur.
Kaptra bu verileri hiçbir yere göndermez.

## Saklama ve silme

Verileriniz yalnızca telefonunuzda ve siz silene kadar durur.

- Bir belgeyi sildiğinizde çöp kutusuna gider ve 30 gün sonra kalıcı olarak
  silinir.
- Kaptra'yı telefonunuzdan kaldırdığınızda Kaptra'nın bütün verileri de
  silinir. Önce dışa aktarmadıysanız belgeleriniz geri getirilemez (bkz.
  "Telefonunuzun yedeği").

Sizinle ilgili hiçbir veri tutmadığımız için erişim, düzeltme ya da silme
talebinde bulunmanıza gerek yok; verileriniz zaten yalnızca sizde.

## Güvenlik

- Kaptra'nın verileri telefonunuzda, uygulamaya ayrılmış depolama alanında
  durur.
- Android bu alanı işletim sistemi düzeyinde yalıtır: başka uygulamalar ona
  erişemez.
- Kaptra verilerinizi hiçbir yere aktarmaz: sunucusu yok, internet izni
  olmadığı için ağ bağlantısı da açamaz. Verileriniz telefondan yalnızca
  sizin başlattığınız paylaşma, dışa aktarma ya da telefondan telefona
  aktarımla çıkar.

## Tarama ve Google Play hizmetleri

Kamera ekranı ve kenar tespiti Kaptra'nın değil, Google Play hizmetlerinin
belge tarayıcısıdır (Google ML Kit). Kamerayı Google Play hizmetleri açar;
Kaptra'nın kamera izni yoktur. Tarama telefonunuzda yapılır ve taranan
sayfalar Kaptra'ya teslim edilir.

- **İlk kullanımda indirme.** Tarayıcı telefonunuzda yoksa Google Play
  hizmetleri onu ilk taramada Google'dan indirir. Bunun için bir kez internet
  bağlantısı gerekir; indirme Kaptra'nın değil Google Play hizmetlerinin
  işidir.
- **Google'ın tanılama verileri.** Google, Google Play hizmetleri üzerinden
  çalışan ML Kit özelliklerinin tanılama ve kullanım istatistiği
  amacıyla veri topladığını belirtiyor: cihaz bilgisi (üretici, model, Android
  sürümü), uygulama bilgisi (paket adı, sürüm), tanılama için bir cihaz
  tanımlayıcısı, işlem süresi gibi performans ölçüleri, görüntü biçimi ve
  çözünürlüğü gibi ayarlar, olay türü ve hata kodları. Google'ın yayımladığı
  bu listede taranan belgenin içeriği yok. Bu veriler Google'a Kaptra
  üzerinden değil, telefonunuzdaki Google Play hizmetleri üzerinden gider ve
  Google'ın gizlilik politikasına tabidir:
  <https://policies.google.com/privacy>. Google'ın listesi:
  <https://developers.google.com/ml-kit/android-data-disclosure>.
- **Tarayıcının Kaptra içindeki parçası.** Tarayıcıyı başlatan küçük bileşen
  Kaptra'nın içinde çalışır ve o da kullanım istatistiği üretir. Bunlar da
  telefonunuzdan çıkamaz: Kaptra'nın internet izni yok (bkz. "Metin
  tanıma").

## Metin tanıma

Metin tanıma (Premium) de Google ML Kit ile yapılır, ama bu bileşen Google
Play hizmetlerinden değil, Kaptra'nın kendi içinden çalışır: tanıma modeli
uygulamanın içinde gelir ve internet gerektirmez. Tanınan metin yalnızca
telefonunuzda, belgenin yanında saklanır.

Google'ın bu bileşeni kendi kullanım istatistiklerini üretir ve Google'a
göndermek üzere telefonda sıraya koyar. Kaptra'nın internet izni olmadığı
için bu istatistikler telefonunuzdan çıkamaz: Android, internet izni olmayan
bir uygulamanın ağ bağlantısı açmasına işletim sistemi düzeyinde izin
vermez. Mağazaya gönderilen sürümde yayından önce doğruladık.

## Satın alma

Premium tek seferlik bir satın almadır ve Google Play'in faturalandırma
sistemiyle yapılır. Ödemeyi Google Play işler; ödeme bilgilerinizi Kaptra
hiçbir zaman görmez. Kaptra yalnızca satın almanın tamamlandığını öğrenir ve
Premium'un açık olduğunu telefonunuzda saklar. Satın alma Google Play'in
kullanım koşullarına ve Google'ın gizlilik politikasına tabidir.

Google'ın satın alma kütüphanesi de kendi kullanım istatistiklerini üretir.
Metin tanımadaki gibi bunlar da telefonunuzdan çıkamaz: Kaptra'nın internet
izni yok ve Android, internet izni olmayan bir uygulamanın ağ bağlantısı
açmasına işletim sistemi düzeyinde izin vermez. Bunu da mağazaya gönderilen
sürümde yayından önce doğruladık.

## İzinler

Kaptra telefonunuzdan yalnızca şu izinleri ister:

- **Ağ durumunu görme.** Tarayıcıyı açmadan önce "bağlantı var mı" sorusunu
  cevaplamak için: tarayıcı henüz inmemişse ve bağlantı yoksa, Google'ın
  çıkışı olmayan hata sayfası yerine Kaptra kendi açıklamasını gösterir. Bu
  izin veri göndermeye yetmez.
- **Google Play faturalandırma.** Premium satın alımı için.

Kamera, fotoğraf, konum, kişiler ve internet izni yoktur.

## Telefonunuzun yedeği

Telefonunuzun yedeği açıksa Android uygulama verilerini Google hesabınıza
yedekler. Kaptra bu yedeğe yalnızca ayarlarını koyar: tema, dil ve
Premium'un açık olduğu. Belgeleriniz ve tanınan metin bu yedeğe girmez.

Yeni bir telefona geçerken iki telefon arasında doğrudan aktarım
yaparsanız belgeleriniz de taşınır. Bu aktarım iki telefon arasında olur,
Google hesabınızdaki yedeğe girmez. Android 8.1 ve öncesinde bu ayrım
yapılamadığı için orada belgeler doğrudan aktarıma da girmez.

Belgelerinizin yedeği için Ayarlar'daki "Tüm belgeleri dışa aktar"ı
kullanın.

## Dışa aktarma ve paylaşma

Bir belgeyi paylaştığınızda ya da bütün belgeleri dışa aktardığınızda dosya,
sizin seçtiğiniz yere ya da uygulamaya gider. Oradan sonrası o uygulamanın ya
da hizmetin koşullarına tabidir. Dışa aktarılan yedek dosyası şifrelenmez:
dosyaya ulaşan herkes içindeki belgeleri görebilir. Kaptra bunu dışa aktarma
anında da söyler.

## Çocuklar

Kaptra çocuklara yönelik değildir.

## Değişiklikler

Bu politika değişirse güncel hali bu sayfada yayımlanır ve yukarıdaki tarih
güncellenir.

## İletişim

Geliştirici: Kaptra

Gizlilikle ilgili sorularınız için:
[kaptra.support@gmail.com](mailto:kaptra.support@gmail.com)
