# Evidence manifest

## Вложения к баг-репортам

- `BUG-001-add-before-load-after-post.png` / `BUG-001-add-before-load-after-get.png` — задача видна после POST 201 и исчезает после позднего GET 200.
- `BUG-002-two-saves-after-second-response.png` / `BUG-002-two-saves-after-late-first-response.png` — второе редактирование отображено и затем перезаписано поздним первым PUT.
- `BUG-003-before-delete-one-of-duplicates.png` / `BUG-003-after-delete-one-of-duplicates.png` — две новые задачи до Delete и отсутствие обеих после одного DELETE `/201`.
- `BUG-003-duplicate-id-multiple-editors.png` — связанное проявление повторного ID: один Edit открывает несколько редакторов.

## Дополнительные наблюдения

Файлы с префиксом `OBS-`, а также `00-`, `01-`, `02-`, `03-` подтверждают дополнительные проверки и не являются отдельными баг-репортами в итоговом документе.

Скриншоты сделаны в основной среде Google Chrome 152.0.7977.64, Windows 11, viewport 1280×900; мобильное наблюдение — viewport 375×812.
