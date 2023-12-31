# Homebrew

## Що таке Homebrew?

Homebrew - це менеджер пакетів для macOS, який дозволяє легко встановлювати і керувати різними програмами та утилітами. Він працює у терміналі і надає зручний спосіб встановлення програм, які можуть бути корисні для розробки, системного адміністрування чи інших завдань.

Щоб уявити це просто, уявіть, що ви хочете встановити новий софт на своєму комп'ютері. Замість того, щоб ручно шукати веб-сайти, завантажувати файли та виконувати складні процеси установки, ви можете використовувати Homebrew. Ви вводите коротку команду в терміналі, і Homebrew автоматично завантажує, встановлює та оновлює програми за вас.

Це робить процес установки програм більш швидким і зручним, особливо для розробників і користувачів, які часто користуються різними інструментами та утилітами у своїй роботі.

## Як встановити Homebrew

Щоб встановити Homebrew на macOS, слідувуйте цим крокам:

1. **Відкрийте Термінал:**
   - Ви можете знайти його в додатках або швидко знайти, використовуючи Spotlight (натискайте `Cmd + Space` і починайте вводити "Terminal").

2. **Вставте команду для встановлення Homebrew:**
   - Скопіюйте та вставте цю команду в термінал і натисніть Enter:
   
   ```bash
     /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
     ```
    
     Ця команда завантажить та встановить Homebrew на ваш комп'ютер.

3. **Дочекайтеся завершення встановлення:**
   - Процес встановлення може зайняти кілька хвилин, в залежності від швидкості вашого Інтернет-з'єднання та інших факторів.

4. **Перевірте встановлення:**
   - Після завершення встановлення введіть команду `brew` в терміналі і натисніть Enter. Якщо Homebrew встановлено правильно, ви повинні побачити інформацію про використання Homebrew.

Тепер ви готові використовувати Homebrew для встановлення різних програм та інструментів на вашому Mac. Зверніть увагу, що для деяких дій може вимагатися введення пароля адміністратора під час встановлення.

- [Як встановити Git?](./how-to-install-git.md)
- [Як встановити Nodejs та npm?](./how-to-install-nodejs-and-npm.md)