# Traffic-sign-recognition

собрана база из 40000 знаков 44 видов и 10000 знаков (без фона, размера не менее 40x40 пикселей) 42 видов,
сделан классификатор, исправлена ошибка с обрезанием изображения
работает обучение с учителем
сделан контурный поиск
реализовано выделение изображений по контурам
добавлены фильтр красного, синего, белого (в соответствии с цветами контуров знаков дорожного движения)
реализовано удаление фона изображения
склеить классификатор и контурный поиск
написана оболочка общения с пользователем
добавлена возможность выведения ответа в csv и вывода изображения с выделенными найденными знаками на первом шаге алгоритма (до удаления фона)
