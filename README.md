# ВходПроверен — умный контроль доступа сотрудников

**«ВходПроверен»** — это современное мобильное приложение для оперативной верификации сотрудников с помощью QR-кода и фотоидентификации. Работник сканирует QR-код со своего телефона, а система автоматически производит проверку личности и фиксирует факт входа.

## 🔧 Как это работает

1. 📲 Сотрудник сканирует QR-код на объекте
2. 🌐 Открывается уникальная веб-страница-заглушка
3. 🔔 На приложение «ВходПроверен» поступает WebSocket-сигнал
4. 📸 Приложение делает фото и отправляет его на сервер
5. 🧠 Сервер (на Go) распознаёт лицо и возвращает информацию о сотруднике
6. ✅ Система отображает результат проверки: **допущен** / ❌ **отказ**

## 💼 Где пригодится

- 🏢 Проходные предприятий и офисов
- ⛺ Вахтовый контроль и удалённые объекты
- 🔧 Выездные бригады и техобслуживание
- 🎓 Образовательные учреждения (проверка студентов)

## 🔒 Преимущества

- Автоматическая верификация без ручных списков
- Повышение безопасности объекта
- Упрощение контроля доступа
- Интеграция с внутренними системами учёта

---

**ВходПроверен** — когда каждый вход под контролем.  
Идеально подходит для компаний, ценящих безопасность и автоматизацию процессов.
