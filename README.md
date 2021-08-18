# Ботнет Telegram аккаунтов

## Для Windows
### Установка

Для установки скачиваем с оффициального сайта [Python](https://www.python.org/downloads/) самой новой версии (текущая 3.9.6)

Теперь запускаем установщик, и обьязательно ставим галочку на пункт
- [x] ADD PYTHON 3.9 to PATH
И ожидаем...
Теперь скачиваем ЮзерБота По этой [Ссылке](https://github.com/X1111X/Bnt/archive/refs/heads/main.zip)
Разархивируем файлы, и запускаем файл windows.bat

### Запуск
Открываем файл windows.bat

---

## Для Termux (Android)

### Установка
```
apt-get update -y ; apt-get install python -y ; apt-get install git -y ; curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py ; python3 get-pip.py ; rm get-pip.py ; git clone https://github.com/X1111X/bnt ; cd bnt ; termux-wake-lock ; pip3 install -r requirements.txt ; python3 bot.py
```

### При запуске
```
cd bnt && termux-wake-lock && python bot.py
```
---

## Для Linux [Debian/Kali]

### Установка
Открываем терминал, и устанавливаем Python и также Git
```
apt install python3 git
```

Теперь мы клонируем репозиторий коммандой
```
git clone https://github.com/X1111X/bnt.git
```

Переходим в директерию с юзерботом
```
cd bnt
```

Устанавливаем зависимости
```
pip3 install -r requirements.txt
```

И запускаем файл через Python
```
python3 bot.py
```

Готово)

### Запуск

Запускаем терминал и пишем такие комманды
```
cd bnt && python3 bot.py
```
---
## [© Botnet Telegram](https://github.com/A9FM/filesUB/blob/main/README.md) 
