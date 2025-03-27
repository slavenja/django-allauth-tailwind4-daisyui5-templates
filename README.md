# Современные шаблоны для Django-Allauth с Tailwind CSS 4 и DaisyUI 5
(screenshot.png)

## Русский

Этот репозиторий предлагает кастомные шаблоны для `django-allauth` на **Tailwind CSS 4** и **DaisyUI 5** для стильного и современного адаптивного дизайна.

### Особенности формы регистрации (`signup.html`)
- **Локализация**: Ориентированна на русскоязычных пользователей! Поля "Имя" (валидация на кириллицу) и "Отчество" (опционально) вместо стандартного "username".
- **Валидация**:
  - HTML5 для клиентской проверки имени и пароля.
  - Серверная валидация через Django с отображением ошибок.
  - **Только для формы регистрации**: Интерактивная проверка силы пароля через **Alpine.js** с прогресс-баром и сообщениями ("Слабый", ..."Сильный").
- **Кастомизация**: Гибкая настройка полей с помощью `django-widget-tweaks`.
- **Дизайн**: Минималистичный и отзывчивый интерфейс с Tailwind CSS и DaisyUI.

### Макеты (`layouts`)
- Стилизованы с использованием Tailwind CSS 4 и DaisyUI 5 - подойдут для всех!

### Технологии
- Django, `django-allauth`, `django-widget-tweaks`.
- Tailwind CSS 4, DaisyUI 5.
- **Alpine.js** (только для формы регистрации).
- HTML5, SVG.

### Установка
1. Склонируйте репозиторий: `git clone https://github.com/<ваш_логин>/allauth-templates.git`.
2. Скопируйте папку `templates/account` в ваш проект.
3. Подключите зависимости: `allauth`, `widget_tweaks`, Tailwind, DaisyUI (и Alpine.js для формы регистрации).

### Вклад
Приветствуются любые улучшения!

---

## English

This repository offers custom templates for `django-allauth` built with **Tailwind CSS 4** and **DaisyUI 5** for a stylish and modern responsive design.

### Signup Form Features (`signup.html`)
- **Localization**: Tailored for Russian-speaking users! "First Name" (Cyrillic validation) and "Patronymic" (optional) fields replace the standard "username".
- **Validation**:
  - HTML5 for client-side validation of name and password.
  - Server-side validation via Django with error display.
  - **Signup form only**: Interactive password strength checker powered by **Alpine.js**, featuring a progress bar and messages ("Weak" to "Strong").
- **Customization**: Flexible field adjustments using `django-widget-tweaks`.
- **Design**: Minimalistic and responsive interface with Tailwind CSS and DaisyUI.

### Layouts (`layouts`)
- Styled with Tailwind CSS 4 and DaisyUI 5 — suitable for everyone!

### Technologies
- Django, `django-allauth`, `django-widget-tweaks`.
- Tailwind CSS 4, DaisyUI 5.
- **Alpine.js** (used only for the signup form).
- HTML5, SVG.

### Installation
1. Clone the repository: `git clone https://github.com/<ваш_логин>/allauth-templates.git`.
2. Copy the `templates/account` folder into your project.
3. Set up dependencies: `allauth`, `widget_tweaks`, Tailwind, DaisyUI (and Alpine.js for the signup form).

### Contribution
Any improvements are welcome!
