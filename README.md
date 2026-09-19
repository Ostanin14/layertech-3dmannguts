# LAYERTECH 3D

Разделённая версия проекта из исходного файла.

## Структура

- `app.py` — Flask backend
- `templates/` — отдельные HTML/Jinja страницы
- `static/css/style.css` — стили
- `static/js/main.js` — JavaScript
- `models.db` — создаётся автоматически при запуске

## Запуск

```bash
pip install -r requirements.txt
python app.py
```

Откройте `http://127.0.0.1:5000`.

## Важно

Проект использует Flask и SQLite, поэтому это не набор полностью статических HTML-файлов: авторизация, корзина, заказы и админ-панель требуют Python backend.