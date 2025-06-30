# SSO Тестирование (ЕЛК Web)

Этот репозиторий содержит автотесты для формы авторизации ЕЛК Web:  
🔗 [https://lk.rt.ru/ ](https://lk.rt.ru/ )

## 🧪 Описание тестов

- `test_login.py`: проверяет успешную и неуспешную авторизацию по телефону.
- Используется Page Object Model для структурирования кода.
- Проверяются валидации, ошибки, редиректы.

## 📦 Требования

- Python 3.8+
- ChromeDriver
- Selenium
- PyTest
- allure-pytest (для отчетов)

## 📥 Установка

```bash
git clone https://github.com/PavelVNazarov/sso_tests.git 
cd sso_tests
pip install -r requirements.txt
