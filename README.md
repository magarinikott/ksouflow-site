# KSOU FLOW site v1

быстрый статический сайт для `ksouflow.tech`.

## что внутри
- `index.html` — landing page
- `privacy.html` — политика конфиденциальности
- `support.html` — поддержка / contact
- `styles.css` — общий стиль
- `i/index.html`, `vk/index.html`, `oauth-callback.html` — служебные страницы в той же палитре Wine & Ivory
- `og-image.png` — социальное превью; исходник для повторной генерации — `assets/og-image-source.html` (1200×630)

## локальный просмотр
из папки `site` можно запустить:

```bash
python3 -m http.server 4173
```

и открыть:

- http://localhost:4173/
- http://localhost:4173/privacy.html
- http://localhost:4173/support.html

## важно
сейчас это v1 под быстрый релиз.
тексты и блоки можно спокойно менять позже без пересборки архитектуры с нуля.
