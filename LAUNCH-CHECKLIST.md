# Yayın Günü Kontrol Listesi

## 1. İçeriği yeniden doğrula

- [ ] Uygulama adı: `RasgeleTör XL` / `Randomizer XL`
- [ ] Paket adı: `com.ozanshow1.randomizerxl`
- [ ] Destek e-postası: `ozaneuysal@gmail.com`
- [ ] Ayrı destek e-postası açıldıysa uygulama, hukuk sayfaları ve Play Console
      aynı adresle güncellendi
- [ ] Play Console geliştirici/yayıncı adı politika ile uyumlu
- [ ] Yürürlük tarihi gerçek public yayın tarihine göre güncel
- [ ] Reklam, analytics, crash reporting veya geliştirici backend’i eklenmedi
- [ ] Google Play Billing dışındaki veri aktarımı eklenmedi
- [ ] Spor Hareketi Seçici hâlâ mevcutsa sağlık/egzersiz açıklamaları korunuyor
- [ ] Play hedef kitlesinde 13 yaş altı seçilmedi ve Families’e katılım yok
- [ ] Gizlilik sayfasındaki 13+ beyanı Play Console hedef kitlesiyle aynı
- [ ] iOS/App Store’da kullanılacaksa Apple ödeme ve gizlilik metni eklendi

## 2. Tek hukuk deposunu yayınla

- [ ] Bu depoyu public yap
- [ ] Settings → Pages → Deploy from a branch → `main` / `(root)` seç
- [ ] Pages dağıtımının tamamlanmasını bekle
- [ ] `.nojekyll`, `index.html`, `privacy.html`, `terms.html` ve `assets/`
      eksiksiz yayınlandı
- [ ] Gizlilik adresi:
      `https://ozaneuysal-max.github.io/RasgeleTor-XL-Legal/`
- [ ] Uygulamadaki gizlilik URL’sinin aynı adres olduğu doğrulandı
- [ ] Önceki imzalı paketler farklı URL içerdiği için Android `versionCode`
      artırıldı
- [ ] Yeni imzalı AAB üret ve doğrula

## 3. URL kontrolleri

- [ ] HTTPS ile açılıyor
- [ ] Şifre/giriş istemiyor
- [ ] Coğrafi engel yok
- [ ] PDF değil, doğrudan HTML
- [ ] Mobil görünüm okunaklı
- [ ] Gizlilik ve Şartlar birbirine bağlı
- [ ] E-posta bağlantısı çalışıyor
- [ ] `index.html` ve `privacy.html` aynı politika içeriğini gösteriyor
- [ ] Play Console’a girilen URL ile uygulamadaki URL aynı politikayı gösteriyor

## 4. Play Console

- [ ] Gizlilik Politikası URL’sini mağaza kaydına ekle
- [ ] Data Safety cevaplarını son AAB ile yeniden karşılaştır
- [ ] Premium ürün ve inceleme erişimini doğrula
- [ ] Uygulamayı önce Internal Testing’e gönder

> `noindex` etiketi sayfayı arama sonuçlarından uzak tutmaya yardımcı olur fakat
> URL’yi bilen herkes sayfayı açabilir. Play incelemesi sırasında sayfa private,
> şifreli veya erişime kapalı olamaz.
