# Форма сбора данных

## Описание проекта
Этот проект – это интегрированное приложение для сбора данных, созданное для взаимодействия с Битрикс24. Приложение позволяет генерировать индивидуальные ссылки для каждого клиента в Битрикс24, обеспечивая безопасный и уникальный доступ к форме сбора данных. Эта форма содержит множество полей, включая такие, как имя, фамилия, отчество, дата рождения, номер и серия паспорта, и многие другие. Все данные подлежат строгой валидации: от формата ввода информации до корректности номера телефона.

После успешного заполнения формы, данные автоматически отправляются в Битрикс, где создается основной контакт, а также четыре дополнительных контакта поручителя. Эти поручители затем привязываются к основному контакту. Важной особенностью системы является ее способность распознавать уже существующие контакты в Битрикс24. Если таковой обнаруживается, данные просто обновляются, исключая дублирование. В завершение процесса, клиенту предоставляется уведомление о успешном заполнении, после чего форма автоматически закрывается, а ссылка становится неактивной

## Назначение проекта
Проект создан для того, чтобы компании было проще собирать и обновлять данные клиентов без лишних ошибок и дубликатов. Благодаря интеграции с Битрикс24, вся информация о клиенте находится в одном месте и доступна всем сотрудникам. Уникальные ссылки для заполнения формы добавляют безопасность, гарантируя, что только нужный клиент может внести изменения. В итоге, это помогает компании лучше работать с данными и обслуживать своих клиентов.

## Галерея

![Изображение 1](https://github.com/BrepeX/bolsun-form/blob/main/screen%201.png)
![Изображение 2](https://github.com/BrepeX/bolsun-form/blob/main/screen%202.png)
![Изображение 3](https://github.com/BrepeX/bolsun-form/blob/main/screen%203.png)
![Изображение 4](https://github.com/BrepeX/bolsun-form/blob/main/screen%204.png)

## Моя роль в проекте
В проекте я был ответственным за разработку front-end части. Обеспечил её безупречную интеграцию с Битрикс24. Одной из ключевых задач, которую я успешно реализовал, было создание кастомного поля в Битрикс, которое генерировало уникальную ссылку для каждого клиента. Эта ссылка основывалась на JWT токенах, которые передавались в URL и использовались для доступа к форме. Мой вклад в проект был направлен на обеспечение удобства и безопасности при работе с данными клиентов.

## Технологии, используемые в проекте
- React
- Typescript
- MUI
- react-hook-form
- mui-tel-input
- Axios

## Принципы и инструменты разработки
- Код-стиль и форматирование: Prettier
- Линтер: ESLint
- Система контроля версий: Git 

## Команда
- Общее количество человек: 2
- Роли в команде:
  - Front-end: 1
  - Back-end: 1

## Основные достижения и результаты
- **Безупречная интеграция с Битрикс24:** Успешно разработали и внедрили механизм, связывающий нашу форму с системой Битрикс24, что автоматизировало сбор и обновление данных клиентов.

- **Уникальная система генерации ссылок:** Создали и внедрили систему на основе JWT токенов для генерации уникальных ссылок для каждого клиента. Это обеспечило дополнительный уровень безопасности и гарантировало, что только соответствующий клиент имеет доступ к его форме.
  
- **Эффективная валидация данных:** Внедрили систему проверки введенной информации на ошибки и дубликаты, что существенно снижает риск ввода некорректных данных.

## Особые вызовы и преодоленные препятствия
- **Интеграция с Битрикс24:** Из-за особенностей API системы Битрикс24 на стадии интеграции возникли сложности. Однако, после изучения документации и нескольких тестовых реализаций, мы успешно преодолели этот этап, обеспечив бесшовную интеграцию.
  
- **Генерация безопасных ссылок:** При создании системы на основе JWT токенов для генерации уникальных ссылок, были проблемы с безопасностью данных. Нам удалось устранить уязвимости, применив дополнительные методы шифрования и проверки.

## Ссылки
- Демо проекта: К сожалению, демонстрационная версия проекта недоступна, так как проект является приватным и для каждого клиента генерируется личная ссылка в портале Битрикс24
- Код проекта: Из-за договора о неразглашении (NDA) я не могу предоставить прямой доступ к коду проекта.

