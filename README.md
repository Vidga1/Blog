# Описание Обновлений Проекта Блога

Это обновление включает в себя значительные улучшения в разработке и поддержке сайта блога. 

## Основные Изменения и Добавления

### Разработка Страниц
- **Создание Основных Страниц:** Реализованы главная страница, страницы постов и контактов.
- **Стилизация с SCSS:** Для улучшения структуры и читабельности кода использован препроцессор SASS.

### Сборка и Линтинг
- **Автоматизированная Сборка:** Использование Gulp и SASS для преобразования SCSS в CSS.
- **Линтинг:** Добавлены конфигурации линтеров для SCSS и HTML, гарантируя качество и соответствие кода стандартам.

### Интеграция Husky Hooks
- **pre-commit:** Проверка кода линтерами перед коммитом, предотвращение добавления некачественного кода.
- **pre-push:** Запуск сборки проекта перед пушем, для подтверждения работоспособности последних изменений.

### GitHub Actions
- **check-lint:** Автоматическая проверка стилей и валидация HTML при пулл-реквестах и пушах.
- **sandbox-link:** Отправка демо-версий на Sandbox для превью.
- **deploy:** Автоматический деплой собранной версии проекта после мерджа в главную ветку.

## Дополнительные Заметки
- **Тщательная Проверка:** Страницы и стили были тщательно проверены с использованием линтеров.
- **Sandbox Превью:** Предварительный просмотр функционала доступен по ссылкам на Sandbox.

Эти обновления значительно улучшают качество и удобство работы с проектом блога, обеспечивая более высокий уровень организации кода и его автоматизированную обработку.
