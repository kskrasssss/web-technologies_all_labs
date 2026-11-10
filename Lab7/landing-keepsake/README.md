# Landing Keepsake — Digital & Branding Agency

Адаптивний односторінковий лендінг для дизайн-агенції **Keepsake**, виконаний у межах Лабораторної роботи №7.

## 🔗 Демонстрація
- **Live Demo (GitHub Pages):** [https://<kskrasssss>.github.io/landing-keepsake/](https://<kskrasssss>.github.io/landing-keepsake/)

## 🛠 Технології та рішення
- **HTML5**: Семантична розмітка (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`).
- **CSS3**:
  - **CSS Variables (`:root`)**: Використано для кольорової палітри, шрифтів, розмірів сітки та відступів.
  - **Flexbox & CSS Grid**: Модульна розкладка елементів, сітка портфоліо та послуг без абсолютного позиціонування.
  - **Mobile First**: Базові стилі для екранів від 320px з використанням `@media (min-width: ...)` для Tablet (768px) та Desktop (1280px).
  - **Чистий CSS Інтерактив**: Реалізація мобільного бургер-меню через `:checked` гамбургер-тригер та фільтрація портфоліо за допомогою радіокнопок і атрибутів без JS.
- **Оптимізація та Доступність**: Інлайн SVG-іконки, підтримка клавіатурного фокусу (`:focus-visible`), коректні атрибути accessibility (`aria-label`, `aria-describedby`).