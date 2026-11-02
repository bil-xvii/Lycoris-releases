# Lycoris — скачать / Download

**Безопасная оптимизация Windows для работы и игр.** Чёрно-белый строгий интерфейс. Каждое изменение записывается в журнал и откатывается в один клик.

## ⬇ [Скачать последнюю версию → Releases](../../releases/latest)

Скачайте `Lycoris.exe` и запустите. Один файл, устанавливать ничего не нужно (.NET внутри). (В версии 1.0.0 файл ещё называется `MONOLITH.exe` — это та же программа.)

- Windows 10 (2004+) / Windows 11, 64-bit.
- Открывается **без запроса прав администратора** в режиме просмотра. Когда вы нажимаете кнопку, которая что-то меняет, Lycoris сам перезапускается с правами администратора и продолжает то же действие.
- Интерфейс: русский / English (Настройки → «Язык / Language»; по умолчанию — язык Windows).
- Перед каждым изменением сохраняется исходное значение и создаётся точка восстановления Windows; любое изменение откатывается.
- Только документированные настройки. Никаких «чисток реестра», отключения обновлений, защитника или файла подкачки.
- Проверка файла: `Get-FileHash Lycoris.exe -Algorithm SHA256` должна совпасть с `Lycoris.exe.sha256` из релиза.
- Файл пока **не подписан** цифровой подписью, поэтому Windows (SmartScreen / окно UAC) может писать «Издатель: неизвестно». Если вы не доверяете файлу — не запускайте его.

---

**Safe Windows optimization for work and gaming.** Every change is journaled and can be undone in one click; a restore point is created before each batch; only documented settings.

**Download:** [latest release](../../releases/latest) → `Lycoris.exe` (single file, Windows 10 2004+/11 64-bit, no installer). Opens read-only without UAC and asks for admin rights only when you press a button that changes something. Language: Russian / English. Verify with `Lycoris.exe.sha256`. Not code-signed yet — Windows may show "Unknown publisher".
