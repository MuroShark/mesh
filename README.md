# РешуЦДЗ 

    
# Текущий статус 🗿
[:warning:] Работает, но бывают ошибки у МЭШ (Иногда нужна авторизация. При авторизации надо поменять `demo = true` на `demo = false` в первых строчках основго файла) (17.02.2021)
    
# Благодарности 🙏
 - Большое спасибо [kinda-cookie-monster](https://github.com/kinda-cookie-monster) за полную переработку библиотеки. [Pull request #1](https://github.com/superdima05/mesh/pull/6) [Pull request #2](https://github.com/superdima05/mesh/pull/7)
 - Большое спасибо https://vk.com/6x88y9 за фикс библиотеки. Обсуждение было [тут](https://github.com/superdima05/mesh/issues/1)
 - Большое спасибо [mishailovic](https://github.com/mishailovic) за нахождения нового endpoint в МЭШ. Обсуждение было [тут](https://github.com/superdima05/mesh/issues/3)
    
# Установка ⚙️
  1. Сколнировать репозиторий `git clone https://github.com/superdima05/mesh`
  2. Скопировать файл `mesh.py` в папку к своему проекту.
  3. В `mesh.py` найти "ЛОГИН К МЭШ" и "ПАРОЛЬ К МЭШ" и изменить их на ваш логин и пароль к МЭШ.
  3. Добавить `import mesh` в вашем проекте
  
# Использование
  [:x:] - Метод не работает
  [:heavy_check_mark:] - Метод работает
  1. [:heavy_check_mark:] Получить номер варинта (если тест имеет только идентификатор) `get_variant(Cсылка на тест. Пример ссылки: https://uchebnik.mos.ru/exam/test/test_by_binding/9792593/homework/120414331?generation_context_type=homework)`
  2. [:warning:] Получить ответы `get_answers(Номер варианта, тип (читать ниже))`. По доп. информации смотреть пункт `Текущий статус`
  3. В тип надо укзать либо 'spec', либо 'homework'. Указываем 'spec', если не использовали метод get_variant(). Если использовали, то используем тип 'homework'
