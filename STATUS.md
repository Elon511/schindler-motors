# Schindler Motors — статус

Обновлено: 18 августа 2026.

- 20 автомобилей, 200 локальных WebP-фото и 20 индивидуальных страниц `/cars/<vehicle-id>/`.
- Концепция: `Memory Lane 1950s`.
- Прямой рекламный URL фиксирует выбранную машину в HERO, отдельном proof-блоке, форме и 10-фото галерее.
- Открыто показываются точные цена и Stock Number.
- Основные действия: `Check Availability` и `Request Walk-Around Video`.
- WhatsApp удалён; оставлены Live Chat и телефон.
- Добавлены заполненные дилерские Privacy Policy и Terms of Use.
- Lead contract: `dealerId=schindler-motors`, `landingId=schindler-motors`, endpoint `/api/leads`; назначение звонарей выполняется серверным Routing, а не браузером.
- Полный QA на 1440×1000 и 390×844: 46/46 комбинаций прошли, 0 failures, 0 accessibility violations, 0 console/page errors, 0 broken local responses и 0 overflow.
- HTML-валидация, JavaScript syntax check и пакетная проверка прошли.
- `demoMode: true`: до платного трафика требуется реальный тест `форма → Google Sheets → Telegram → назначенный звонарь`, операторский live chat, подтверждение данных дилера и юридическое согласование политик.

Отчёт: `../WebOpsStudio/reports/qa-03_Schindler_Motors.json`.
