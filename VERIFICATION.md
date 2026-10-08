# Doğrulama / Verification

Chrome eklentisi Opera'da (Chromium tabanlı) paketlenmemiş uzantı olarak yüklenip denendi. Mobil cihaz testi yapıldı. Kaynak: kullanıcının 8 Ekim 2026 bildirimi; cihaz ve test akışı ayrıntıları belirtilmedi. AI Brief Asistanı anahtarsız demo modunda.

The Chrome extension was loaded and tested in Opera (Chromium-based) as an unpacked extension. Mobile device testing was performed. Source: the author's report dated 8 October 2026; device and test-flow details were not specified. AI Brief Assistant is in key-free demo mode.

8 Ekim / October 2026

- 10 benzersiz repo ve iki demo bağlantısı CV/portföy verilerinde mevcut. / Ten unique repository links and two demo links are present in CV/portfolio data.
- DOM simülasyonu: TR/EN geçişi, dil bazında CV adresleri, kategori filtreleri ve iki demo düğmesi geçti. / DOM simulation passed for language switching, language-specific CV links, category filters and two demo buttons.
- Yerel varlık yolları ve CV kopyalarının eşitliği kontrol edildi. JavaScript sözdizimi kontrolü geçti. / Local asset paths and matching CV copies checked. JavaScript syntax check passed.
- Repo/yayın adresleri kullanıcı tarafından bildirildi; uzaktan bağlantı kontrolü yapılmadı. / Repo/demo addresses supplied by the author; remote availability not checked.
- Tarayıcı görsel QA, ekran okuyucu denemesi ve PDF tek sayfa doğrulaması yapılmadı. / Browser visual QA, screen-reader testing and one-page PDF verification not performed.
- Proje kartlarındaki test sayıları önceki yerel doğrulama kayıtlarına dayanır; bu içerik güncellemesinde tüm proje testleri yeniden çalıştırılmadı. / Project test counts refer to prior local verification records; the full project suites were not rerun for this content update.
- Telegram: kullanıcının 8 Ekim 2026 bildirimiyle /add, /list, /done ve /lang gerçek Telegram botuyla elle test edildi. / Telegram: according to the author's report dated 8 October 2026, /add, /list, /done and /lang were manually tested with a real Telegram bot.
- Docker: kullanıcının 8 Ekim 2026 bildirimiyle Docker Desktop/Compose üzerinden çalıştırıldı; healthy konteyner, /docs, GET /health 200, GET /products 200 ve POST /products 201 elle doğrulandı; Compose ile kapatıldı. PATCH, DELETE ve /summary yalnızca otomatik testlerle doğrulandı. / Docker: according to the author's report dated 8 October 2026, run with Docker Desktop/Compose; healthy container, /docs, GET /health 200, GET /products 200 and POST /products 201 manually verified, then stopped with Compose. PATCH, DELETE and /summary validated only by automated tests.
