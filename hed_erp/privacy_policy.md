# Политика конфиденциальности приложения Spherix

Дата вступления в силу: 20 ноября 2026 г.

Spherix (com.erp.apk) — корпоративное ERP-приложение для сотрудников компании. Аккаунты создаёт администратор компании; самостоятельная регистрация в приложении недоступна. В этой политике описано, какие данные собирает приложение, зачем и как они используются.

## Какие данные мы собираем

Данные аккаунта. Номер телефона и пароль, выданные компанией, используются для входа. Для быстрого входа по PIN-коду они сохраняются на устройстве.

Местоположение. Приложение собирает точное местоположение устройства (геолокацию) в двух случаях:

- Когда сотрудник сам включает функцию «Рабочая смена». Местоположение записывается постоянно, в том числе когда приложение свёрнуто, закрыто или не используется, — до тех пор, пока сотрудник не выключит смену или не выйдет из аккаунта. Перед первым включением приложение показывает уведомление о сборе данных и запрашивает согласие. Пока смена включена, на экране устройства отображается постоянное уведомление. Вместе с координатами сохраняются время их получения и признак того, получено ли местоположение от приложения для подмены геолокации.
- Когда сотрудник в открытом приложении добавляет или изменяет данные клиента (клиента, контактное лицо, адрес, запись о посещении). Местоположение определяется однократно, чтобы зафиксировать место, где сделана запись.

Фото лица. При входе в приложение для подтверждения личности сотрудника используется фронтальная камера. Изображение с камеры анализируется на самом устройстве; на сервер отправляется только одно фото лица. Фото, сделанное при первой регистрации, используется для создания шаблона лица (набора чисел), который хранится на сервере компании; само фото не сохраняется. Фото, сделанные при последующих проверках, используются только для сравнения с шаблоном и не сохраняются.

Сообщения, фотографии и файлы. Сообщения в чате, фотографии и файлы, которые пользователь сам отправляет или прикрепляет в приложении (чат, задачи, документы, история клиентов, логистика).

Идентификаторы устройства. Токен Firebase Cloud Messaging, необходимый для доставки push-уведомлений.

## Как мы используем данные

- для работы функций приложения и входа в аккаунт;
- для подтверждения личности сотрудника при входе (проверка лица);
- для учёта перемещений сотрудников и посещений клиентов в рабочее время;
- для выявления поддельного местоположения;
- для отправки уведомлений о сообщениях и задачах.

Мы не используем данные для рекламы и не показываем рекламу в приложении.

## Передача данных

Данные передаются только на серверы компании-работодателя. Мы не продаём и не передаём пользовательские данные третьим лицам. Для доставки push-уведомлений используется сервис Google Firebase Cloud Messaging, который обрабатывает данные по поручению разработчика. Для анализа изображения с камеры на устройстве используется Google ML Kit: изображения не передаются в Google, но библиотека может отправлять в Google технические данные об устройстве и своей работе для диагностики.

## Хранение и защита

Записи о местоположении хранятся на устройстве до отправки на сервер; отправленные записи удаляются с устройства через 7 дней. На серверах компании данные хранятся в течение срока, установленного внутренними правилами компании. Шаблон лица хранится, пока у сотрудника есть учётная запись, и удаляется вместе с ней; доступ к шаблонам имеют только уполномоченные сотрудники компании. Мы принимаем разумные меры для защиты данных, однако ни один способ передачи данных по сети не обеспечивает полную безопасность.

## Ваш выбор
- Вы можете отказаться от согласия на сбор местоположения в окне согласия — в этом случае смена не включится.
- Вы можете в любой момент выключить смену; запись местоположения при этом прекращается.
- Вы можете отозвать разрешение на доступ к местоположению в настройках устройства.
- Проверка лица обязательна для входа в приложение. Чтобы удалить шаблон лица, обратитесь к администратору компании или по адресу, указанному ниже.
- По вопросам доступа к вашим данным или их удаления обратитесь к администратору вашей компании или по адресу, указанному ниже.

## Дети

Приложение предназначено для сотрудников компании и не предназначено для детей.

## Изменения

Мы можем обновлять эту политику. Актуальная версия всегда доступна по этой ссылке.

## Контакты

jamshid.mayakupov@gmail.com

---

# Spherix Privacy Policy

Effective date: November 20, 2026

Spherix (com.erp.apk) is a corporate ERP app for company employees. Accounts are created by the company administrator; users cannot register in the app. This policy describes what data the app collects and how it is used.

## Data we collect

Account data. The phone number and password issued by the company are used to sign in. They are stored on the device to enable PIN sign-in.

Location. The app collects the device's precise location in two cases:

- When the employee turns on the "Рабочая смена" (Work shift) feature. Location is recorded continuously, including when the app is minimized, closed or not in use, until the employee turns the shift off or signs out. Before the first start the app shows a disclosure and asks for consent. While the shift is on, a persistent notification is shown on the device. Each location is stored with the time it was obtained and a flag showing whether it came from a location-spoofing app.
- When the employee, with the app open, adds or edits client data (a client, a contact person, an address or a visit record). Location is obtained once to record where the entry was made.

Face photo. At sign-in the front camera is used to confirm the employee's identity. The camera image is analyzed on the device; only one face photo is sent to the server. The photo taken at first registration is used to create a face template (a set of numbers) that is stored on the company's server; the photo itself is not stored. Photos taken during later checks are used only for comparison with the template and are not stored.

Messages, photos and files that the user sends or attaches in the app (chat, tasks, documents, client history, logistics).

Device identifiers. The Firebase Cloud Messaging token needed to deliver push notifications.

## How we use data

- to provide app features and sign-in;
- to confirm the employee's identity at sign-in (face check);
- to account for employees' movements and client visits during working hours;
- to detect spoofed locations;
- to send notifications about messages and tasks.

We do not use data for advertising and the app shows no ads.

## Data sharing

Data is sent only to the employer company's servers. We do not sell or share user data with third parties. Google Firebase Cloud Messaging is used, on the developer's behalf, to deliver push notifications. Google ML Kit is used to analyze the camera image on the device: images are not sent to Google, but the library may send technical data about the device and its own operation to Google for diagnostics.

## Retention and security

Location records are kept on the device until they are uploaded; uploaded records are deleted from the device after 7 days. On the company's servers data is kept for the period set by the company's internal rules. The face template is kept while the employee has an account and is deleted together with it; only authorized company staff can access templates. We take reasonable measures to protect data, but no method of transmission over a network is completely secure.

## Your choices
- You can decline location collection in the consent dialog; the shift then does not start.
- You can turn the shift off at any time; location recording stops.
- You can revoke location permission in the device settings.
- The face check is required to sign in. To delete your face template, contact your company administrator or the address below.
- For access to or deletion of your data, contact your company administrator or the address below.

## Children

The app is intended for company employees and is not directed at children.

## Changes

We may update this policy. The current version is always available at this link.

## Contact

jamshid.mayakupov@gmail.com
