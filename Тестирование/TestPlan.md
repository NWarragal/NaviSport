### Содержание
  1. [Введение](#1)
  2. [Объект тестирования](#2)
  3. [Риски](#3)
  4. [Аспекты тестирования](#4)<br>
    4.1. [Возможность начать игру](#001)<br>
    4.2. [Возможность изменить громкость музыки и звуковых эффектов](#002)<br>
    4.3. [Возможность поставить игру на паузу](#003)<br>
    4.4. [Возможность перезапустить уровень](#004)<br>
    4.5. [Возможность передвижения персонажа](#005)<br>
    4.6. [Возможность передвижения ботов](#006)<br>
    4.7. [Возможность устанавливать бомбу](#007)<br>
    4.8. [Возможность смерти персонажа и бота](#008)<br>
    4.9. [Возможность корректного завершения игры](#009)<br>
5. [Подходы к тестированию](#5)
6. [Представление результатов](#6)
7. [Выводы](#7)

<a name="1"></a>
### 1. Введение
Этот план был разработан для тестирования приложения "Bomberman". 
Цель тестирования - проверка работоспособности и пригодности приложения для практического использования.

<a name="2"></a>
### 2. Объект тестирования
Объект тестирования представляет собой Action-игру для платформы Windows, которая должна обладать следующими атрибутами качества:
1. Функциональность:
    - функциональная полнота: приложение должно выполнять все заявленные функции в соответствии с SRS
    - функциональная корректность: приложение должно выполнять все заявленные функции безошибочно
    - функциональная целесообразность: отсутствуют не заявленные функции, которые бы мешали приложению выполнять первоначально поставленные задачи.

<a name="3"></a>
### 3. Риски
1. Приложение может не запуститься на устройстве с версией Windows ниже чем версия Windows XP


<a name="4"></a>
### 4. Аспекты тестирования
В ходе тестирования должна быть проверена реализация основных функций приложения, к которым относятся:

- Возможность начать игру;
- Возможность изменить громкость музыки и звуковых эффектов;
- Возможность поставить игру на паузу;
- Возможность перезапустить уровень;
- Возможность передвижения персонажа;
- Возможность передвижения ботов;
- Возможность устанавливать бомбу;
- Возможность смерти персонажа и бота;
- Возможность корректного завершения игры

#### Функциональные требования:

<a name="001"></a>
##### Возможность начать игру
Этот вариант использования небходимо протестировать на:
1. Реакцию приложения после нажатия кнопки "Play".
2. Переход из главного меню в режим игры.

<a name="002"></a>
##### Возможность изменить громкость музыки и звуковых эффектов
Этот вариант использования небходимо протестировать на:
1. Переход на окно настроек после нажатия кнопки "Settings".
2. Повышение и понижение громкости при движение ползунка.

<a name="003"></a>
##### Возможность поставить игру на паузу
Этот вариант использования небходимо протестировать на:
1. Приостановку всех действий в игре, после нажатия кнопки паузы.

<a name="004"></a>
##### Возможность перезапуска уровня
Этот вариант использования небходимо протестировать на:
1. Корректный перезапуск уровня игры, после нажатия кнопки

<a name="005"></a>
##### Возможность передвижения персонажа
Этот вариант использования небходимо протестировать на:
1. Корректное передвижение персонажа после нажатия соответствующих кнопок.  

<a name="006"></a>
##### Возможность передвижения ботов
Этот вариант использования небходимо протестировать на:
1. После старта игры проверить корректное передвижение ботов.


<a name="007"></a>
##### Возможность устанавливать бомбу
Этот вариант использования небходимо протестировать на:
1. Корректное устанавливание бомбы, после нажатия кнопки "SPASE" на клавиатуре.

<a name="008"></a>
##### Возможность смерти персонажа и бота
Этот вариант использования небходимо протестировать на:
1. Смерть персонажа или бота босле столкновения с огнём.


<a name="009"></a>
##### Возможность корректного завершения игры
Этот вариант использования небходимо протестировать на:
1. Возможность прохождения уровня.
2. Выход в главное меню.

#### Нефункциональные требования:
- Приложение не должно вылетать и работать корректно.

<a name="5"></a>
### 5. Подходы к тестированию
Тестирование каждого аспекта будет проводиться ручным подходом

<a name="6"></a>
### 6. Представление результатов
Результаты тестирования представлены в [таблице](https://github.com/NikitaKapitanov750503/NaviSport/blob/master/%D0%A2%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5/TestResults.md).

<a name="7"></a>
### 7. Выводы
Данный тестовый план позволяет протестировать основной функционал приложения. Успешное прохождение всех тестов не гарантирует полной работоспособности на всех версиях платформ и архитектурах, однако позволяет полагать, что данное программное обеспечение работает корректно.
