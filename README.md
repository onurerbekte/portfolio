# Onur Erbekte — Portföy / Portfolio

## Türkçe
Statik, iki dilli ve mobil uyumlu kişisel portföy. Hakkımda, 10 proje, kategori filtresi, iletişim bağlantıları ve TR/EN CV içerir. Projeler: **Kurgusal demo proje**. Müşteri deneyimi iddia edilmez.

Dosyaları yerel sunucuda aç: bu klasörde `python -m http.server 8080` çalıştır, http://localhost:8080 adresine git. Derleme veya API anahtarı gerekmez.

### GitHub Pages yükleme
1. Kendi hesabında public `portfolio` reposunu oluştur. Bu klasörün içeriğini repo köküne koy; `cv` klasörünü de ekle.
2. Kendi terminalinde bu klasörde: `git remote add origin https://github.com/onurerbekte/portfolio.git`, ardından `git push -u origin main`. Remote varsa doğru adresi kendin kontrol et.
3. Repo Settings → Pages → Deploy from a branch → main → /(root) → Save.
4. GitHub yayını tamamlayınca beklenen adres: https://onurerbekte.github.io/portfolio/ . Bu adres henüz yayınlanmış olarak doğrulanmadı.
5. TR/EN geçişini, filtreleri, mobil görünümü ve CV bağlantılarını tarayıcıda kontrol et. CV HTML’de Yazdır → PDF olarak kaydet; A4, %100 ölçek, üstbilgi/altbilgi kapalı. Hazır PDF’ler tek sayfa olarak doğrulandı.

Repo ve iki demo adresi kullanıcı beyanına dayanır; public repo adları GitHub API üzerinden giriş yapılmadan kontrol edildi. Docker/Telegram/OpenAI/Chrome test sınırları kartlarda gösterilir. Mobil projede bağımlılık denetiminde 22 kayıt (7 orta, 15 yüksek) raporlandı; üretim öncesi uyumlu bağımlılık düzeltmeleri gerekir. Mola görsel kontrolü kullanıcı tarafından Opera’da yapıldı; TR/EN CV PDF’leri tek sayfa olarak kontrol edildi.

## English
Buildless, bilingual, responsive portfolio with About, 10 projects, category filters, contact links and TR/EN CVs. All showcased projects are fictional demos, with no client experience claimed.

Serve this folder using `python -m http.server 8080` and visit http://localhost:8080. Create your own public `portfolio` repository, upload these files at its root, push the main branch, then select Settings → Pages → Deploy from a branch → main → /(root). Expected address after your deployment: https://onurerbekte.github.io/portfolio/ (not yet verified as published). Assets use relative paths.

Check language switching, filters, responsive layout and CV links in your browser. Print the CV HTML to PDF using A4, 100% scaling and no browser headers/footers; the supplied PDFs have been verified as single-page documents.

Repository/demo addresses were supplied by the author; public repository names were checked through the GitHub API without login. Test limits appear on project cards. The mobile dependency audit reported 22 entries (7 moderate, 15 high); compatible dependency remediation is needed before production. The author visually checked Mola in Opera; TR/EN CV PDFs were verified as single-page documents.
