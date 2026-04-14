# CI/CD Web Project 🚀

![CI Status](https://github.com/merlinnor16-oss/ci-cd-web-project/actions/workflows/ci.yml/badge.svg)

**Живое демо:** [https://merlinnor16-oss.github.io/ci-cd-web-project/](https://merlinnor16-oss.github.io/ci-cd-web-project/)

Этот проект представляет собой полностью автоматизированный **CI/CD конвейер** для типового веб-приложения.

## 🛠 Технологии
* **Node.js** — среда выполнения
* **Jest** — юнит-тестирование
* **ESLint** — линтинг и проверка стиля
* **GitHub Actions** — автоматизация конвейера (CI/CD)
* **GitHub Pages** — хостинг проекта

## 📋 Как работает конвейер?
При каждом `git push` в ветку `main` робот GitHub выполняет следующие шаги:

1. **Continuous Integration (CI):**
   * Устанавливает зависимости.
   * Проверяет код на ошибки с помощью **ESLint**.
   * Запускает тесты через **Jest**.
2. **Continuous Deployment (CD):**
   * Если все тесты прошли успешно, проект автоматически собирается и публикуется на **GitHub Pages**.

## 🚀 Локальный запуск
1. Клонировать: `git clone https://github.com/merlinnor16-oss/ci-cd-web-project.git`
2. Установить зависимости: `npm install`
3. Запустить тесты: `npm test`