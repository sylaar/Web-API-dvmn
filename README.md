# Обрезка ссылок с помощью VK

Скрипт для создания короткой ссылки или получения статистики по уже созданной короткой ссылке.

### Как установить

*Переменные окружения:*  
`VK_TOKEN`  - токен приложения Vk

*Как получить токен:*
1. Создать приложение:  
https://dev.vk.com/ru/admin/created-apps-list?nocode=true
2. Перейти в настркойки приложения:  
https://dev.vk.com/ru/admin/app-settings/{YOUR_APP_ID}/info
3. В меню "Разработка" выбрать "Ключи доступа"  
https://dev.vk.com/ru/admin/app-settings/{YOUR_APP_ID}/info/keys
4. Скопировать "Сервисный ключ" - это и есть VK_TOKEN, используемый в данном скрипте.

Python3 должен быть уже установлен. 
Затем используйте `pip` (или `pip3`, есть конфликт с Python2) для установки зависимостей:
```
pip install -r requirements.txt
```

### Цель проекта

Код написан в образовательных целях на онлайн-курсе для веб-разработчиков [dvmn.org](https://dvmn.org/).

### Пример запуска

```
git clone https://github.com/sylaar/dvmn.git
pip install -r requirements.txt
cd lesson_2
python3 script.py https://dvmn.org/
```