[![Static Badge](https://img.shields.io/badge/Telegram-Channel-Link?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/cubesminingpool)

[![Static Badge](https://img.shields.io/badge/Telegram-Chat-yes?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/cubesminingpool)

[![Static Badge](https://img.shields.io/badge/Telegram-Bot%20Link-Link?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/cubesonthewater_bot?)


## Рекомендация перед использованием

# 🔥🔥 Используйте PYTHON 3.10 🔥🔥

> 🇪🇳 README in english available [here](README.md)

## Функционал  
| Функционал                                                      | Поддерживается |
|-----------------------------------------------------------------|:--------------:|
| Многопоточность                                                 |       ✅        |
| Привязка прокси к сессии                                        |       ✅        |
| Автоматическая добыча блоков                                    |       ✅        |
| Автоматический сбор боксов с пула / клана / называйте как хотите |       ✅        |
| Авто реферал                                                    |       ✅        |
| Поддержка tdata / pyrogram .session / telethon .session         |       ✅        |


## [Настройки](https://github.com/TheEmperorGh/CubesBot/blob/main/.env-example/)
| Настройка                        |                                             Описание                                              |
|----------------------------------|:-------------------------------------------------------------------------------------------------:|
| **API_ID / API_HASH**            |              Данные платформы, с которой запускать сессию Telegram (сток - Android)               | 
| **TIME_BETWEEN_RECEIVING_BOXES** | Время между сбором мистери блоков с пула / клана / зовите как хотите (по умолчанию - [3600, 7200] |
| **REF_ID**                       |                            Аргумент после ?start= в реферальной ссылке                            |
| **USE_PROXY_FROM_FILE**          |              Использовать-ли прокси из файла `bot/config/proxies.txt` (True / False)              |

## Быстрый старт 📚

Для быстрой установки и последующего запуска - запустите файл run.bat на Windows или run.sh на Линукс

## Предварительные условия
Прежде чем начать, убедитесь, что у вас установлено следующее:
- [Python](https://www.python.org/downloads/) **версии 3.10**

## Получение API ключей
1. Перейдите на сайт [my.telegram.org](https://my.telegram.org) и войдите в систему, используя свой номер телефона.
2. Выберите **"API development tools"** и заполните форму для регистрации нового приложения.
3. Запишите `API_ID` и `API_HASH` в файле `.env`, предоставленные после регистрации вашего приложения.

## Установка
Вы можете скачать [**Репозиторий**](https://github.com/TheEmperorGh/CubesBot) клонированием на вашу систему и установкой необходимых зависимостей:
```shell
git clone https://github.com/TheEmperorGh/CubesBot.git
cd CubesBot
```

Затем для автоматической установки введите:

Windows:
```shell
run.bat
```

Linux:
```shell
run.sh
```

# Linux ручная установка
```shell
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt
cp .env-example .env
nano .env  # Здесь вы обязательно должны указать ваши API_ID и API_HASH , остальное берется по умолчанию
python3 main.py
```

Также для быстрого запуска вы можете использовать аргументы, например:
```shell
~/CubesBot >>> python3 main.py --action (1/2)
# Or
~/CubesBot >>> python3 main.py -a (1/2)

# 1 - Запускает кликер
# 2 - Создает сессию
```


# Windows ручная установка
```shell
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
copy .env-example .env
# Указываете ваши API_ID и API_HASH, остальное берется по умолчанию
python main.py
```

Также для быстрого запуска вы можете использовать аргументы, например:
```shell
~/CubesBot >>> python main.py --action (1/2)
# Или
~/CubesBot >>> python main.py -a (1/2)

# 1 - Запускает кликер
# 2 - Создает сессию
```




### Контакты

Для поддержки или вопросов, свяжитесь со мной в Telegram: [@UNKNXWNPLXYA](https://t.me/theemperorte)
