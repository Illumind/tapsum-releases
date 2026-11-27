# Tapsum — Політика конфіденційності / Privacy Policy / Polityka prywatności

Набуває чинності: 26.11.2026 · Effective: 26 Nov 2026 · Obowiązuje od: 26.11.2026

---

## Українською

**Коротко:** усі ваші дані зберігаються лише на вашому телефоні. Tapsum не має серверів, не створює акаунтів і не передає інформацію про ваші покупки нікому.

### Які дані обробляє додаток
- **Сповіщення платіжних застосунків** (Samsung Wallet, Google Wallet, банки зі списку в налаштуваннях). Tapsum читає текст сповіщення лише для того, щоб визначити суму, валюту, магазин, останні 4 цифри картки й тип операції. Сповіщення інших застосунків не читаються, якщо ви самі не ввімкнете «Читати всі додатки».
- **Покупки, категорії, ліміти й налаштування**, які створює додаток або ви вводите вручну.
- **Нерозпізнані сповіщення** платіжних застосунків, у яких є сума. Вони зберігаються до 30 днів, щоб ви могли додати їх вручну.
- **NFC-мітки:** лише ідентифікатор мітки, щоб запам'ятати прив'язаний магазин.

Усе це зберігається в приватному сховищі додатку на телефоні.

### Що надсилається в інтернет
- **Курси валют НБУ** (bank.gov.ua). Додаток запитує офіційний курс на конкретну дату. У запиті є лише дата: ні сум, ні магазинів, ні будь-яких ваших даних.
- **Перевірка оновлень** (раз на день): запит до api.github.com про останню версію Tapsum і, якщо ви натиснете «Оновити», завантаження APK з GitHub. Жодних ваших даних у запитах немає.
- **monobank API (лише якщо ви самі підключили).** Tapsum з вашим особистим токеном запитує виписку напряму з api.monobank.ua; дані йдуть з банку на телефон. Токен зберігається на телефоні, зашифрований Android Keystore, і нікуди, крім api.monobank.ua, не надсилається. Відключення видаляє токен.
- Більше нічого. Аналітики, трекерів і реклами у версіях без реклами немає.

### Резервні копії
Резервну копію створюєте лише ви, і зберігається вона туди, куди ви виберете: на телефон, у Google Drive, OneDrive тощо. Копія зашифрована вашим паролем (AES-256-GCM). Без пароля її не прочитати ні хмарному сервісу, ні розробнику. Пароль автобекапу зберігається на телефоні під захистом Android Keystore.

### Реклама (якщо з'явиться)
Якщо в безкоштовній версії буде реклама, рекламна мережа не отримає даних про ваші покупки. Перед показом персоналізованої реклами з'явиться запит згоди відповідно до GDPR. Підписка Tapsum Plus прибирає рекламу.

### Ваші права
Ви можете будь-коли переглянути, змінити, експортувати (CSV, Excel) або видалити свої дані в додатку. Видалення додатку видаляє всі дані з телефона. Резервні копії, які ви зберегли в інших місцях, видаляєте ви самі.

### Діти
Додаток не призначений для дітей до 13 років і свідомо не збирає їхніх даних.

### Контакти
Питання щодо конфіденційності: через розділ Issues на github.com/Illumind/tapsum-releases.

---

## English

**In short:** all your data stays on your phone. Tapsum has no servers, no accounts and does not share information about your purchases with anyone.

- **Payment notifications** from Samsung Wallet, Google Wallet and banks listed in Settings are read only to extract the amount, currency, merchant, last 4 card digits and transaction type. Other apps' notifications are not read unless you turn on "Read all apps".
- Purchases, categories, limits, settings, unrecognised payment notifications (kept up to 30 days) and NFC tag IDs are stored in the app's private storage on your phone.
- **monobank API (only if you connect it):** with your personal token Tapsum fetches your statement directly from api.monobank.ua; the token is stored encrypted (Android Keystore) and sent only to api.monobank.ua.
- **Update check** once a day (api.github.com) and, if you tap Update, downloading the APK from GitHub; no personal data is sent.
- **Internet:** otherwise only to fetch official exchange rates from the National Bank of Ukraine (bank.gov.ua). The request contains a date only, with no amounts, merchants or personal data. No analytics, no trackers.
- **Backups** are created only by you and saved where you choose. They are encrypted with your password (AES-256-GCM) and cannot be read without it. The auto-backup password is stored on the device, protected by Android Keystore.
- **Ads (if introduced):** ad networks receive no purchase data; GDPR consent is requested before personalised ads. Tapsum Plus removes ads.
- You can view, edit, export (CSV/Excel) or delete your data at any time. Uninstalling removes all data from the phone.
- Not directed at children under 13.
- Contact: Issues at github.com/Illumind/tapsum-releases.

---

## Polski

**W skrócie:** wszystkie dane zostają w Twoim telefonie. Tapsum nie ma serwerów ani kont i nikomu nie przekazuje informacji o Twoich zakupach.

- **Powiadomienia płatnicze** z Samsung Wallet, Google Wallet i banków z listy w Ustawieniach są odczytywane wyłącznie w celu ustalenia kwoty, waluty, sklepu, 4 ostatnich cyfr karty i typu operacji. Powiadomienia innych aplikacji nie są czytane, chyba że włączysz „Czytaj wszystkie aplikacje”.
- Zakupy, kategorie, limity, ustawienia, nierozpoznane powiadomienia płatnicze (do 30 dni) i identyfikatory tagów NFC są przechowywane w prywatnej pamięci aplikacji w telefonie.
- **monobank API (tylko jeśli je połączysz):** z Twoim osobistym tokenem Tapsum pobiera wyciąg bezpośrednio z api.monobank.ua; token jest zaszyfrowany (Android Keystore) i wysyłany tylko do api.monobank.ua.
- **Sprawdzanie aktualizacji** raz dziennie (api.github.com) i pobranie APK z GitHub po naciśnięciu „Aktualizuj”; bez danych osobowych.
- **Internet:** poza tym tylko do pobrania oficjalnych kursów walut Narodowego Banku Ukrainy (bank.gov.ua). Zapytanie zawiera wyłącznie datę: bez kwot, sklepów ani danych osobowych. Brak analityki i trackerów.
- **Kopie zapasowe** tworzysz wyłącznie Ty i zapisujesz je, gdzie chcesz. Są szyfrowane Twoim hasłem (AES-256-GCM) i nie da się ich odczytać bez niego. Hasło kopii automatycznej jest przechowywane w telefonie i chronione przez Android Keystore.
- **Reklamy (jeśli się pojawią):** sieci reklamowe nie otrzymują danych o zakupach; przed reklamami spersonalizowanymi pytamy o zgodę zgodnie z RODO. Tapsum Plus usuwa reklamy.
- Możesz w każdej chwili przeglądać, edytować, eksportować (CSV/Excel) lub usuwać swoje dane. Odinstalowanie usuwa wszystkie dane z telefonu.
- Aplikacja nie jest skierowana do dzieci poniżej 13 lat.
- Kontakt: Issues na github.com/Illumind/tapsum-releases.
