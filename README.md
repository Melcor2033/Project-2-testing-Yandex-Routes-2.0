В данной версии приложения Яндекс Маршрута, было проведенно тестирование следующей функциональности: 
Формы “Добавление прав” и “Добавление карты”, были проведены тесты по состоянию кнопок “Добавить”, “Отмена”, “Привязать”, “Крестик” в зависимости от заполненности полей форм, а также наличие и корректное отображение плейсхолдеров в полях; 
Валидацию полей “Откуда” и “Куда”, были проведены доступные тесты на граничные значения (Т.к в системе заранее заложены корректные адреса, нет возможности проверить валидацию полей при количестве символов равному 50 и более), а также тесты на допустимые (Русские буквы, цифры, пробел, тире, точка, запятая) и недопустимые значения (Буквы латинского языка, спецсимволы, буквы иного языка). Провести проверку на предмет существующий/несуществующий адрес невозможно, так как в данной версии приложения система принимает только заранее заложенные 7 адресов.
Реализация на фронтенде нового вида транспорта (Аэротакси), были проведены тесты по: Отображению иконки и названия нового вида транспорта; Верстку панели выбора транспорта; Отображение стоимости и времени маршрута, изменение состояния значка при клике или смены режима.
