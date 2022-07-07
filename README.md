# GUI
Простая работа с оформлением проекта в консоли.
### На данный момент в библиотеке реализованы следующие функции:
 - Изменение цвета текста;
 - Изменение шрифта текста;
 - Открытие консоли в полный экран;
 - Постановка курсора в нужную позицию;
 - Частичная очистка экрана;
 - Вывод строк победы, поражение и строки по желанию посередине строки консоли;
 - Вывод строки в рамке;
 - Загрузка;
 - Получение координата клика;
 - Меню.
### Изменения:
 - Теперь GUI - пространство имён. 
 - Исправлен баг с Menu, не позволяющий работать с одним стандартным файлом.
 - Теперь при нажатии Enter в стандартном значении 0 функция Menu завершит работу с кодом 0 соответственно. 
 - Исправлен баг, при котором левое и правое нажатие кнопки мыши возвращают одни и те же значения, теперь отсчёт координат начинается с 1.
 - Теперь FilePrint не приватная функция.
##### Для корректной работы в Cion необходимо прописать в CMakeLists следующее:
  add_executable(имя_проекта main.cpp GUI.cpp)
Вместо уже существующей подобной строки.
##### Для корректной работы в Code::Blocks:
  Добавляем данные файлы в проект через меню File.
