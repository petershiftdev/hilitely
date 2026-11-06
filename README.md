# Политика конфиденциальности Hilitely

Публичная страница: https://petershiftdev.github.io/hilitely/

В этом репозитории только политика. Исходники расширения здесь не лежат.

Страницу публикует workflow `.github/workflows/pages.yml`: он копирует `store/privacy-policy/privacy-policy.html` как `index.html`. В кабинет магазина вставляется адрес без якоря. Язык берётся из браузера; свой адрес у каждого языка, например `#ru`.

Те же файлы правятся в проекте Hilitely, в папке `store/privacy-policy/`, затем копируются сюда и отправляются в `main`.

Репозиторий остаётся публичным. Settings → Pages → Source: **GitHub Actions**.
