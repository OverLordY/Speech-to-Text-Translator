# Speech-to-Text Translator v1.4

[Українська](#українська) · [English](#english) · [Deutsch](#deutsch)

[Завантаження та опис на OverLeX.eu](https://overlex.eu/uk/translators.html) · [Повідомити про помилку](https://github.com/OverLordY/Speech-to-Text-Translator/issues/new)

## Українська

Програма для розпізнавання та перекладу мовлення із системного звуку Windows: лекцій, відео або онлайн-конференцій. Deepgram розпізнає англійську чи німецьку мову, а DeepL перекладає завершені фрази українською.

### Можливості

- Захоплення системного звуку, відображення оригіналу й перекладу.
- Збереження кожної сесії у TXT і формування багатосторінкового PDF після зупинки.
- Відновлення PDF із TXT під час наступного запуску після аварійного завершення.
- Зберігання введених ключів у захищеному сховищі Windows DPAPI для поточного облікового запису.

### Перший запуск

1. Завантажте **ZIP** з офіційного сайту й розпакуйте весь вміст у папку.
2. Запустіть EXE, залишивши папку **_internal** поруч: вона містить необхідні залежності.
3. Введіть власні ключі Deepgram і DeepL, оберіть джерело системного звуку та мову.
4. Запустіть сесію. TXT зберігається під час роботи; після зупинки створюється PDF.

Версія 1.4 — опублікована збірка. Транскрипти зберігаються локально; мовлення та текст передаються обраним хмарним сервісам для обробки.

### Вимоги та конфіденційність

Windows x64, інтернет, відповідні аудіопристрої та власні доступи до обраних сервісів. Залежно від провайдера, користування API може бути платним; перевіряйте актуальні умови у провайдера. Інсталяція віртуального кабелю, якщо він потрібен, виконується окремо. Дані передаються стороннім сервісам для обробки.

Завантажуйте програму лише з [офіційної сторінки OverLeX](https://overlex.eu/uk/translators.html). В Issues опишіть версію Windows, кроки відтворення та очікуваний результат. **Не публікуйте API-ключі, токени, особисті дані або приватні записи розмов.**

## English

A Windows system-audio transcription and translation tool for lectures, video and online meetings. Deepgram recognizes English or German; DeepL translates finalized phrases into Ukrainian. Sessions are saved as TXT and PDF, with PDF recovery after a crash. Download and extract the entire ZIP: the executable needs the accompanying _internal folder.

[Download and requirements](https://overlex.eu/en/translators.html) · [Report an issue](https://github.com/OverLordY/Speech-to-Text-Translator/issues/new)

Requires Windows x64, internet and your own credentials for the selected services. Third-party usage may be billed. Do not post API keys or private recordings in public issues.

## Deutsch

Ein Windows-Werkzeug zur Transkription und Übersetzung von Systemaudio, etwa aus Vorlesungen, Videos oder Konferenzen. Deepgram erkennt Englisch oder Deutsch; DeepL übersetzt abgeschlossene Äußerungen ins Ukrainische. Sitzungen werden als TXT und PDF gespeichert; nach einem Absturz kann das PDF aus dem TXT wiederhergestellt werden. Bitte das gesamte ZIP entpacken: Die EXE benötigt den Ordner _internal.

[Download und Voraussetzungen](https://overlex.eu/de/translators.html) · [Fehler melden](https://github.com/OverLordY/Speech-to-Text-Translator/issues/new)

Erforderlich sind Windows x64, Internet und eigene Zugangsdaten für die ausgewählten Dienste. Drittanbieter können Gebühren berechnen. Bitte keine API-Schlüssel oder privaten Aufnahmen in öffentlichen Issues veröffentlichen.

## Source code and distribution

This public repository is a project overview and support page. Source code, API keys and user recordings are **not published here**. Download the application from the official OverLeX website linked above. Availability and behavior of third-party services may change.
