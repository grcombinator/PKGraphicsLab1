# PKGraphicsLab1
ЦВЕТОВЫЕ МОДЕЛИ И ПРИЛОЖЕНИЯ ДЛЯ РАБОТЫ С ЦВЕТОМ.

Описание проекта.

Данное приложение позволяет пользователям интерактивно выбирать и изменять цвет, отображая его составляющие в трех цветовых моделях одновременно: RGB, CMYK и LAB. Пользователи могут вводить точные значения, выбирать цвета из палитры и изменять их с помощью ползунков. Приложение также обрабатывает некорректные цвета, выдавая предупреждения при необходимости.

Зависимости.

Для сборки и запуска приложения требуется следующее:

Qt 5.15 или выше: Библиотека для разработки кроссплатформенных приложений.
C++11 или выше: Стандарт языка программирования.
CMake (если используется для сборки).
Инструкция по сборке.

Клонируйте репозиторий:
bash

Copy
git clone https://github.com/grcombinator/PKGraphicsLab1.git

cd grcombinator

Создайте папку для сборки:
bash

Copy
mkdir build
cd build
Запустите CMake:

bash

Copy
cmake ..
Соберите проект:

bash

Copy
cmake --build .
Запустите приложение:
bash

Copy
./Ваше_приложение
Изображения
Прилагаются скриншоты интерфейса приложения для ознакомления с функционалом:

![image](https://github.com/user-attachments/assets/96a4a4a0-d9da-4bd6-a5d8-32695ce342fd)

Функционал приложения- Выбор цвета: Пользователь может выбрать цвет из палитры.- Интерактивное изменение цвета: Изменение значений через ползунки, что автоматически обновляет другие цветовые модели.- Точные значения: Ввод значений в текстовые поля для RGB, CMYK и LAB.- Обработка некорректных значений: Приложение выдает предупреждение, если вычисленные значения выходят за пределы допустимых диапазонов.### Пределы входных данных- RGB: Значения должны находиться в диапазоне от 0 до 255.- CMYK: Значения должны находиться в диапазоне от 0.0 до 1.0 (где 0.0 означает 0%, а 1.0 — 100%).- LAB: Значения L должны быть в диапазоне от 0 до 100, а a и b — от -128 до 127.### Как запустить и посмотреть тесты1. Запустите приложение как описано выше.2. Для запуска тестов (если включены в проект): - Перейдите в директорию сборки. - Запустите тесты командой: bash     ctest     3. Просмотр результатов тестов будет выведен в консоль, где можно узнать, прошли ли тесты успешно.### ЗаключениеДанное приложение является эффективным инструментом для работы с цветами, позволяя пользователям интуитивно взаимодействовать с различными цветовыми моделями. 