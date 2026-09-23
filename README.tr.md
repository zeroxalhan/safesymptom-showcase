<h1 align="center">SafeSymptom</h1>

<p align="center">
<strong>AI destekli ilk değerlendirme. Birbirine bağlı doktor iş akışları.</strong><br>
<em>Bağımsız geliştirilen, kapalı kaynak bir ürün demosu.</em>
</p>

<p align="center">
<a href="https://www.safesymptom.com"><strong>Demoyu incele ↗</strong></a>
&nbsp; · &nbsp; <a href="README.md">English</a>
&nbsp; · &nbsp; <a href="#screenshots">Ekran görüntüleri</a>
&nbsp; · &nbsp; <a href="#contact">İletişim</a>
</p>

![SafeSymptom herkese açık ana sayfası, masaüstü](assets/screenshots/home-tr-desktop.png)

<p align="center"><strong>Türkçe + İngilizce</strong> &nbsp; · &nbsp; Masaüstü + mobil &nbsp; · &nbsp; <strong>Kaynak kod gizli kalır</strong></p>

## Çıkış noktası

Semptom sohbeti, bir sağlık iş akışının yalnızca bir parçasıdır. **Toplanan bağlamın sonraki aşamalara da taşınması gerekir.** SafeSymptom bu bağlantıyı tek bir uygulamada araştırıyor: hasta girişi ve değerlendirme özetlerinden doktor sohbetine ve aktarıma kadar.

<table>
<tr>
<td width="72" align="center"><img src="assets/icons/conversation.png" alt="" width="44" height="44"></td>
<td><strong>Yönlendirmeli sohbet</strong><br>Takip soruları, değerlendirme tamamlanmadan önce senaryonun bağlamını toplar.</td>
</tr>
<tr>
<td width="72" align="center"><img src="assets/icons/report.png" alt="" width="44" height="44"></td>
<td><strong>Yapılandırılmış bilgi</strong><br>Özetler ve aciliyet kategorileri, sohbeti incelenebilir bir biçime taşır.</td>
</tr>
<tr>
<td width="72" align="center"><img src="assets/icons/handoff.png" alt="" width="44" height="44"></td>
<td><strong>Bağlantılı aktarım</strong><br>Doktorlar arası aktarımda görüşmelerin yazarları ve geçmişi korunur.</td>
</tr>
</table>

> **Demo kapsamı:** Yalnızca 18 yaş ve üzeri kullanıcıların kurgusal senaryoları test etmesi içindir. SafeSymptom teşhis koymaz veya gerçek sağlık hizmeti sunmaz. Doktor, randevu ve reçete akışları tanıtım amaçlıdır. Gerçek sağlık bilgisi, hasta kimliği veya tıbbi belge girmeyin. Acil durumlarda bulunduğunuz yerin acil yardım hizmetine başvurun.

<a id="screenshots"></a>

## Uygulamadan görüntüler

*Herkese açık sayfalar canlı demodan alınmıştır. Giriş gerektiren ekranlarda gerçek arayüz, yerel ve kurgusal test verileriyle gösterilir. Sohbet metni örnek amaçlı yazılmıştır; kaydedilmiş bir model değerlendirmesi değildir.* [Görüntüler nasıl hazırlandı?](SCREENSHOTS.md)

### 01 · Hasta sohbeti

Takip soruları, değerlendirme tamamlanmadan önce kurgusal senaryonun bağlamını toplar.

![Kurgusal test mesajlarıyla hasta sohbeti](assets/screenshots/patient-chat-tr-desktop.png)

<details>
<summary><strong>Mobil sohbeti görüntüle</strong></summary>

<p align="center"><img src="assets/screenshots/patient-chat-tr-mobile.png" alt="Kurgusal test mesajlarıyla mobil hasta sohbeti" width="390"></p>

</details>

### 02 · Doktor geçmişi ve aktarım

**Aktarım, önceki görüşmenin bağlamını kaybettirmemeli.** Doktor çalışma alanı; raporları, hasta geçmişini, sohbeti ve notları rol bazlı erişimle bir araya getirir. Bu salt okunur örnekte hedef doktor ve aktarım zamanı kurgusal test kimlikleriyle gösterilir.

![Kurgusal kayıtlarla doktor geçmişi ve transfer edilmiş görüşme](assets/screenshots/clinician-history-tr-desktop.png)

### 03 · Gizlilik tercihleri

<img src="assets/icons/privacy.png" alt="" width="36" height="36"> &nbsp; **Dışa aktarma, izni geri çekme ve silme talebi ayrı işlemlerdir.**

<details>
<summary><strong>Gizlilik Merkezi'ni incele</strong></summary>

*Bu yerel testte izin geri çekilmiştir. Diğer gizlilik kontrolleri erişilebilir kalır.*

![Dışa aktarma, izni geri çekme ve silme talebi kontrolleriyle Gizlilik Merkezi](assets/screenshots/privacy-center-tr-desktop.png)

</details>

## Canlı demoyu deneyin

1. **[SafeSymptom'u](https://www.safesymptom.com) açın.**
2. **Google ile giriş yapın;** katılım koşullarını, aydınlatma metnini ve kullanım koşullarını inceleyin.
3. **Yalnızca uydurulmuş bir senaryo kullanın.** Google hesap bilgileriniz yine gerçektir; bu bilgilerin işlenmesi Gizlilik Bildirimi'nde açıklanır.

Model kullanımı sınırlıdır; bakım veya kullanım sınırları nedeniyle demo geçici olarak erişilemeyebilir. Doktor erişimi ayrıca yetkilendirilir; hasta girişi doktor çalışma alanına erişim sağlamaz. Gerçek doktor bulunabilirliği veya görüşmesi vaat edilmez.

[Gizlilik Bildirimi](https://www.safesymptom.com/privacy) · [Kullanım Koşulları](https://www.safesymptom.com/terms) · [Gizlilik Merkezi](https://www.safesymptom.com/privacy-center)

## Teknik odak

<img src="assets/icons/engineering.png" alt="" width="36" height="36"> &nbsp; **TypeScript · Next.js · PostgreSQL / Supabase · Sunucu taraflı AI entegrasyonu**

- **Süreklilik:** kalıcı sohbet durumu ve bağlantılı aktarım geçmişi.
- **Kontrollü erişim:** rol bazlı klinik iş akışları ve açık onay.
- **Veri koruma:** seçili alanların uygulama düzeyinde şifrelenmesi ve kesintiden sonra devam edebilen arka plan işlemleri.
- **Kullanılabilirlik:** iki dil ve farklı ekranlara uyumlu hasta/doktor arayüzleri.

*SafeSymptom bağımsızdır. Canlı Epic/FHIR entegrasyonu, klinik doğrulama veya mevzuat sertifikasyonu iddiası yoktur. Arayüz görüntüleri ve yazılım testleri tıbbi doğruluk kanıtı değildir.*

## Kaynak kod ve haklar

Projenin sahibi ve geliştiricisi **Alhan Akdemir**'dir.

**Bu bir ürün tanıtımıdır, açık kaynak yayını değildir.** Repo yalnızca belgeler, ekran görüntüleri ve görsel öğeler içerir. Uygulamanın kaynak kodu gizli kalır; MIT veya başka bir açık kaynak yazılım lisansı verilmez.

Copyright © 2026 Alhan Akdemir. Özel hak bildirimi, sınırlı tanıtım paylaşımı ve üçüncü taraf haklarına ilişkin istisnalar için [LICENSE](LICENSE) dosyasına bakın. Herkese açık GitHub dosyaları GitHub koşulları kapsamında görüntülenebilir ve fork edilebilir; bu, uygulama kaynak koduna lisans verildiği anlamına gelmez.

<a id="contact"></a>

## İletişim

<img src="assets/icons/contact.png" alt="" width="36" height="36"> &nbsp; **Geri bildirim, iş birliği veya bir sorunuz mu var?**

| Konu | İletişim |
| :--- | :--- |
| Geri bildirim, teknik sorunlar, iş birliği | [support@safesymptom.com](mailto:support@safesymptom.com) |
| Gizlilik ve kişisel veri talepleri | [privacy@safesymptom.com](mailto:privacy@safesymptom.com) |
| Güvenlik sorunları | [Özel bildirim yönergeleri](SECURITY.md) |

<details>
<summary><strong>Mevcut İletişim bölümünü görüntüle</strong></summary>

Mevcut İletişim bölümü destek ve gizlilik e-posta bağlantıları sunar. Uygulama içi destek formu henüz mevcut demoda yer almaz.

![Destek ve gizlilik e-posta bağlantılarıyla İletişim bölümü](assets/screenshots/contact-tr-desktop.png)

</details>

**E-posta veya herkese açık GitHub tartışmalarında sağlık bilgisi, erişim anahtarı ya da hassas kişisel bilgi paylaşmayın.**
