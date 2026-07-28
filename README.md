# RasgeleTör XL Legal

RasgeleTör XL için Türkçe ve İngilizce Gizlilik Politikası ile Hizmet
Şartları kaynaklarıdır.

## Şu anki durum

- GitHub deposu **private** tutulmalıdır.
- GitHub Pages **açılmamalıdır**.
- HTML sayfalarında `noindex, nofollow, noarchive` bulunur.
- Harici font, JavaScript, analiz veya takip kodu kullanılmaz.

## Dosyalar

- `index.html`: Tam Gizlilik Politikası. Play Console gizlilik URL’si doğrudan
  bu içeriği göstermelidir.
- `privacy.html`: `index.html` ile aynı politikanın alternatif adresi.
- `terms.html`: Hizmet Şartları.
- `assets/legal.css`: Mobil uyumlu, takipsiz stil dosyası.
- `LAUNCH-CHECKLIST.md`: Yayın günü adımları.

## Planlanan private depo

`https://github.com/ozaneuysal-max/RasgeleTor-XL-Legal`

Bu depo Pages için açılırsa planlanan adresler:

- Gizlilik: `https://ozaneuysal-max.github.io/RasgeleTor-XL-Legal/`
- Alternatif gizlilik:
  `https://ozaneuysal-max.github.io/RasgeleTor-XL-Legal/privacy.html`
- Şartlar:
  `https://ozaneuysal-max.github.io/RasgeleTor-XL-Legal/terms.html`

## Kritik URL notu

Mevcut Android uygulaması şu eski adresi açıyor:

`https://duzdunyaarilari-a11y.github.io/randomizer-xl-privacy/`

Yayın gününde iki güvenli seçenek vardır:

1. **Mevcut AAB’yi korumak:** Bu depodaki `.nojekyll`, `index.html`,
   `privacy.html`, `terms.html` ve `assets/` dosyalarını eski Pages deposuna
   aktarın. Uygulama bağlantısı değişmez.
2. **Yeni Pages adresini kullanmak:** Uygulamadaki sabit gizlilik URL’sini yeni
   adrese değiştirin, Android `versionCode` değerini artırın ve yeni AAB üretin.

Sadece yeni private depoyu public yapmak mevcut AAB içindeki eski bağlantıyı
değiştirmez.

## Yayın öncesi doğrulanacak bilgi

Play Console’daki geliştirici/yayıncı adı farklıysa politika metnine aynı resmî
ad eklenmelidir. Uygulama adı ve paket adı sayfalarda zaten açıkça yer alır.

Metin şu anda Android/Google Play yayınına göre hazırlanmıştır. Aynı URL ileride
App Store’da kullanılacaksa Apple ödeme, geri yükleme ve gizlilik bağlantıları
eklenmeden yayınlanmamalıdır.

Bu taslak hukuki danışmanlık yerine geçmez. Özel bir şirket yapısı, farklı ülke
mevzuatı veya ek veri işleme özelliği devreye girerse metin yeniden
değerlendirilmelidir.
