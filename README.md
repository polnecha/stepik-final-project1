# Финальный проект курса по автоматизации тестирования на Selenium и Python

Автотесты для интернет-магазина http://selenium1py.pythonanywhere.com/,
написанные по паттерну Page Object.

## Структура

- `pages/` — Page Object: `BasePage`, `MainPage`, `LoginPage`, `ProductPage`, `BasketPage` и локаторы
- `test_main_page.py` — тесты главной страницы
- `test_product_page.py` — тесты страницы товара
- `conftest.py` — фикстура `browser` и параметры `--browser_name`, `--language`

## Запуск

```bash
pip install -r requirements.txt
pytest -v --tb=line --language=en -m need_review
```
