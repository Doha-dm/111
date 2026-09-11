Создать виртуальное окружение:
python -m venv .venv

Активировать виртуальное окружение в Windows PowerShell:
.\.venv\Scripts\Activate.ps1

После активации в терминале должно появиться:
(.venv)

Установить зависимости из файла requirements.txt:
python -m pip install -r requirements.txt

Запустить все тесты:
python -m pytest
