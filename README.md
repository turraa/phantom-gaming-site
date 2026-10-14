# Phantom Gaming — сайт компьютерного клуба

Одностраничный лендинг для PC-клуба **Phantom Gaming** (Ростов-на-Дону, пр. Мира 12Б).

## Локальный просмотр

```bash
cd phantom
python -m http.server 8123
```

Откройте: http://localhost:8123/

## Структура

```
phantom/
├── index.html          # страница + Schema.org (LocalBusiness, FAQ, Offer)
├── robots.txt
├── sitemap.xml
├── css/styles.css
├── js/main.js
└── assets/
    ├── img/            # фото залов, логотип, OG-картинка
    └── video/          # фоновое видео героя
```

## Перед публикацией

1. Купите/подключите домен и **замените** `https://phantom-gaming.ru` во всех файлах
   (`index.html`, `robots.txt`, `sitemap.xml`) на ваш реальный адрес.
2. Залейте содержимое папки на хостинг (Beget, Timeweb, Reg.ru, GitHub Pages, Cloudflare Pages).
3. Добавьте сайт в [Яндекс.Вебмастер](https://webmaster.yandex.ru/) и Google Search Console,
   укажите `sitemap.xml`.
4. Проверьте карточки организации в Яндекс.Бизнес — ссылка на сайт должна совпадать.

## SEO, что уже сделано

- Title / Description под локальные запросы («компьютерный клуб Ростов-на-Дону»)
- Open Graph + Twitter Card
- JSON-LD: LocalBusiness, FAQPage, Offers с тарифами
- FAQ из 8 вопросов (в т.ч. под голосовой поиск)
- SEO-текст внизу страницы с гео-маркерами (Сельмаш, пр. Мира, 24/7)
- `robots.txt` + `sitemap.xml`
- WebP + сжатые JPG, лёгкое фоновое видео (~680 КБ)
- Адаптив, sticky CTA на мобильных, карта Яндекса

## Контакты в коде

| Поле | Значение |
|------|----------|
| Адрес | Ростов-на-Дону, пр. Мира 12Б |
| Телефон | +7 (909) 437-55-33 |
| Telegram | https://t.me/Phantom_gamingrnd |
| Карта | https://yandex.ru/maps/-/CXBV6Kzz |
