# РешуЦДЗ 

    
# Текущий статус 🗿
  [:heavy_check_mark:] Библиотека в рабочем состоянии (31.08.2021).
    
# Благодарности 🙏
 - Большое спасибо [kinda-cookie-monster](https://github.com/kinda-cookie-monster) за полную переработку библиотеки. [Pull request #1](https://github.com/superdima05/mesh/pull/6) [Pull request #2](https://github.com/superdima05/mesh/pull/7)
 - Большое спасибо https://vk.com/6x88y9 за фикс библиотеки. Обсуждение было [тут](https://github.com/superdima05/mesh/issues/1)
 - Большое спасибо [mishailovic](https://github.com/mishailovic) за нахождения нового endpoint в МЭШ. Обсуждение было [тут](https://github.com/superdima05/mesh/issues/3)

# Проекты, основанные на этой библиотеке
   - [Telegram бот](https://t.me/CDSansbot), Разработчик: [zsaz](https://github.com/superdima05)
   - [Сайт](https://mash.hotaru.ga/), Разработчик: [mishailovic](https://github.com/mishailovic)
   - launcher.py (Находится в этом репозитории), Разработчик: [kinda-cookie-monster](https://github.com/kinda-cookie-monster)

# Установка ⚙️
  1. Сколнируйте репозиторий. Если у вас стоит консольный git, введите: `git clone https://github.com/superdima05/mesh.git`.
  2. Скопируйте файл `mesh.py` в папку вашего проекта.
  3. Добавьте `import mesh` в ваш проект.

# Пример получения ответов на тест
```python
    import mesh
    answers = mesh.get_answers("https://uchebnik.mos.ru/exam/test/view_test/191202/")
    for i in answers:
        print(i[0], i[1])
```

# А что это за файл - launcher.py?
    Это отдельное приложение, которое основано на данной библтотеке, и является ярким примером использования различных функций, которые вам доступны. Также на случай, если вам быстро нужны ответы на тест или вы занимаетесь разработкой библиотеки, эта консольная программка также поможет в этом.

    1. Склонируете репозиторий. Если у вас стоит консольный Git, введите: `git clone https://github.com/superdima05/mesh.git`.
    2. Зайдите в только что склонированный репозиторий.
    3. Введите: `python (или python3, в зависимости от вашей системы) launcher.py --help`, чтобы увидеть все доступные параметры.
