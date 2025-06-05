# Skycast

<div align="center">
    <img src="skycast/images/logo_icon.ico" alt="Skycast logo" width="120" />
    <p>Your friend to view the weather</p>
    <p><a href="https://t.me/psevdocoders">💬 Telegram channel</a></p>
</div>

Skycast — простое и быстрое приложение для просмотра погоды по координатам. Без отслеживания данных и лишних функций.

## Содержание
- [Skycast](#skycast)
  - [Содержание](#содержание)
  - [Требования](#требования)
  - [Установка](#установка)
  - [Использование](#использование)
  - [API](#api)
  - [GUI Описание](#gui-описание)
    - [Основные элементы:](#основные-элементы)
    - [Особенности:](#особенности)
  - [Для разработчиков](#для-разработчиков)
  - [Лицензия](#лицензия)

## Требования
- Python 3.13+
- Git
- Зависимости из `requirements.txt`

## Установка
1. Установите Python: [python.org](https://www.python.org/downloads/).
2. Клонируйте репозиторий:
   
bash
   git clone https://github.com/omniuser209/skycast.git
   cd skycast
  
3. Создайте и активируйте виртуальное окружение:
   - Windows: `python -m venv venv` и `venv\Scripts\activate`
   - Linux/macOS: `python3 -m venv venv` и `source venv/bin/activate`
4. Установите зависимости:
   
bash
   pip install -r requirements.txt
  

## Использование
1. Запустите приложение:
```bash
python UI_thread.py
```   

2. Введите координаты (например, `55.7558, 37.6173` для Москвы) в правой панели.
3. Нажмите «Обновить».
4. Пример результата:
   - Город: Москва
   - Температура: 20°C
   - Погода: Ясно
   - Влажность: 60%
   - Скорость ветра: 5 м/с

![Скриншот интерфейса](skycast/images/screenshot.png)
## API
Skycast использует [Open-Meteo API](https://open-meteo.com/) для получения данных о погоде. Используемые параметры:
- latitude, longitude: Координаты локации.
- Данные: температура, влажность, скорость ветра, описание погоды.

## GUI Описание
### Основные элементы:
- Поле ввода координат: Для указания широты и долготы.
- Область отображения погоды:
  - Название города
  - Текущая температура
  - Описание погоды (ясно, облачно и т.д.)
  - Влажность
  - Скорость ветра
  - Иконка погоды

### Особенности:
- Темная и светлая темы.
- Валидация ввода координат.
- Обработка ошибок API.
- Поддержка двух языков: русский, английский.

## Для разработчиков
- Кодстайл: Следуйте PEP 8.
- Структура проекта:
  - UI_thread.py: Основной файл для запуска GUI.
  - requirements.txt: Список зависимостей.
  - skycast/images/: Иконки и изображения.
- .gitignore: Игнорирует venv/, __pycache__/, .env.
- Контрибьютинг:
  1. Создайте ветку: git checkout -b feature/имя-ветки
  2. Закоммитьте изменения: git commit -m "Добавлена фича"
  3. Отправьте: git push origin feature/имя-ветки
  4. Создайте Pull Request.


## Лицензия

Copyright (c) 2025 [Omniuser209]

Этот проект распространяется под лицензией GNU General Public License версии 3.0. Подробности см. в файле [LICENSE](LICENSE).

Вопросы и предложения: [psevdocoders.dev@gmail.com](mailto:psevdocoders.dev@gmail.com)  
Telegram: [t.me/psevdocoders](https://t.me/psevdocoders)

*Последнее обновление: 2025-06-04*
`

---
