# LocalFlow для Mac

Диктовка голосом в любое окно. Зажал клавишу, сказал, отпустил — текст
появился там, где стоит курсор. Работает без интернета: речь не уходит
никуда с компьютера.

## Установка

1. Скачай `LocalFlow-….dmg` со страницы
   [Releases](https://github.com/1nebog/localflow-mac/releases/latest).
2. Открой файл и перетащи **LocalFlow** в папку «Программы».
3. Открой «Программы», нажми на LocalFlow **правой кнопкой → Открыть**, затем
   ещё раз **Открыть**. Так нужно один раз: у программы нет платной подписи Apple.
4. Разреши **Микрофон**, **Отслеживание ввода** и **Универсальный доступ**
   (Системные настройки → Конфиденциальность и безопасность).
5. Первый раз программа скачает модель распознавания (1,5 ГБ, 5–10 минут).
   Пока идёт загрузка, в строке меню стоит значок ⇣. Дальше интернет не нужен.

Нужен Mac с чипом Apple (M1 и новее) и macOS 14 или новее.

## Как пользоваться

- **Зажми левый Option** и говори. Отпустил — текст вставился.
- **Коротко нажми** — запись идёт сама. Закончить — нажми ещё раз.
- Значок волны в строке меню: настройки, словарь, история.

## Обновление

Значок волны в строке меню → панель → **Настройки** → **Обновления** →
**Проверить**. Если есть новая версия — **Обновить**: LocalFlow сама скачает
её, поставит и перезапустится. Разрешения сохраняются.

## Текст не вставляется, хотя галочки стоят

Если ставил LocalFlow 0.1.9 и новее вручную поверх, галочка может остаться от старой копии. Открой
Универсальный доступ, выбери LocalFlow, нажми «−», затем «+» и добавь LocalFlow
из «Программ» заново. Потом закрой LocalFlow и открой снова.

---

# LocalFlow for Mac

Dictate into any window. Hold a key, speak, release — the text appears at the
cursor. Fully offline: your voice never leaves the computer.

## Install

1. Download `LocalFlow-….dmg` from
   [Releases](https://github.com/1nebog/localflow-mac/releases/latest).
2. Open it and drag **LocalFlow** into **Applications**.
3. In Applications, **right-click LocalFlow → Open**, then **Open** again.
   Only needed once: the app is not signed with a paid Apple certificate.
4. Allow **Microphone**, **Input Monitoring** and **Accessibility**
   (System Settings → Privacy & Security).
5. On first launch it downloads the speech model (1.5 GB, 5–10 minutes). A ⇣
   icon shows in the menu bar meanwhile. After that no internet is needed.

Requires an Apple-silicon Mac (M1 or newer) and macOS 14 or later.

## Use

- **Hold left Option** and speak. Release — the text is inserted.
- **Tap briefly** to record hands-free; tap again to stop.
- The wave icon in the menu bar: settings, dictionary, history.

## Updating

Wave icon in the menu bar → panel → **Settings** → **Updates** → **Check**.
If there is a new version, click **Update**: LocalFlow downloads it, installs
it and restarts by itself. Permissions are kept.

## Text isn't inserted although the switches are on

If you installed a new version by hand over 0.1.9, the switch can belong to the old copy. In Accessibility select
LocalFlow, click “−”, then “+” and add LocalFlow from Applications again.
Then quit and reopen LocalFlow.
