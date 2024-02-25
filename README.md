## Solenox Project Reborn 
### Server

### ВНИМАНИЕ! ИЗ ДАННОГО РЕПОЗИТОРИЯ УБРАНЫ ПЛАГИНЫ ДЛЯ СЕРВЕРА И ЗАМЕНЕНО ЕГО ЯДРО.

### Описание

Этот репозиторий содержит ИСКЛЮЧИТЕЛЬНО сборки сервера, обеспечивающий уникальный игровой процесс для игроков на версии 1.12.2.

### Ветви Репозитория

* **master:** Стабильная ветвь, содержащая последнюю протестированную и пофикшенную сборку.
* **beta:** Ветка для тестирования новых функций и изменений перед объединением со стабильной веткой.
* **bleeding-edge:** Ветка для получения свежайших сборок (данная ветка крайне нестабильна).
* **testing:** Ветка для изолированного тестирования конкретных функций или исправлений ошибок.

### Процесс Разработки

* Разработчиком создается эксперементальная сборка и заливается в ветвь bleeding-edge.
* Если при тестировании ветви bleeding-edge не выявлено критический ошибок, то она объединяется с ветвью testing, где происходит дальнейшее тестирование сборки.
* После тестирования сборки и устраниения ошибок в сборке, она отправляется в ветвь beta, где происходит автоматическое тестирование и окончательный багфикс.
* В конечном итоге, сборка попадает в ветвь master и отправляется на сервера обновлений     

### Приступая к работе

**1. Клонирование репозитория:**

```bash
git clone https://github.com/Solenox-Project/Server.git
```

**2. Установка зависимостей:**

Для корректной работы сервера необходимо установить следующие зависимости:

* Java Development Kit (JDK) 8
* Forge Mod Loader для Minecraft 1.12.2 и соотвествующие модификации к нему

**3. Запуск сервера:**

Запустите файл `start.sh` или `start.bat`. Также можно запустить JAR-файл сервера с помощью команды `java` с соответствующими аргументами.

**4. Настройка сервера под себя:**

Отредактируйте файл `server.properties` для настройки параметров сервера, таких как игровой режим, сложность, генерация мира и т. д. При необходимости рассмотрите возможность редактирования конфигов модификаций.


### Вклад

Мы приветствуем участие сообщества! Чтобы внести свой вклад, читайте дальнейшие инструкции в файле `CONTIRUBING.md`

### Лицензия

Этот проект лицензирован под Solenox Project Open Source. Подробнее см. файл `LICENSE`.
