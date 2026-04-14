# CI/CD Web Project 🚀

![CI Status](https://github.com/merlinnor16-oss/ci-cd-web-project/actions/workflows/ci.yml/badge.svg)

Учебный проект по настройке **Continuous Integration** (непрерывной интеграции) с использованием GitHub Actions.

## 🛠 Технологии
* **Node.js** — среда выполнения
* **Jest** — автоматическое тестирование
* **ESLint** — проверка качества и стиля кода (линтинг)
* **GitHub Actions** — автоматизация пайплайна

## 📋 Что делает этот проект?
При каждом `git push` в ветку `main` автоматически запускается цепочка проверок:
1. **Установка зависимостей**: Проверка, что проект собирается с нуля.
2. **Lint**: Поиск ошибок в синтаксисе и стиле кода.
3. **Tests**: Запуск юнит-тестов для проверки бизнес-логики.

Если хотя бы один этап падает — значок в начале этого файла станет красным, сигнализируя об ошибке.

## 🚀 Как запустить локально
1. Клонировать репозиторий:
   ```bash
   git clone [https://github.com/merlinnor16-oss/ci-cd-web-project.git](https://github.com/merlinnor16-oss/ci-cd-web-project.git)