# Отчет
В качестве модели классификатора взял EfficientNet, реализованы следующие дополнения:
#LBL1 Использование аугментации: 
      RandomBrightnessContrast - стандартная аугментация, изменяет контрастность изображения
      HorizontalFlip, VerticalFlip, Rotate - геометрические аугментации, связанные с поворотом, отражением изображений,
                                             в данной задаче их уместно использовать, т.к. у клеток нет определенного положения в пространстве
#LBL2 Валидация модели на части обучающей выборки
#LBL3 Дополнительное улучшение(lr, убывающий по косинусу)
#LBL4 Вывод различных показателей в процессе обучения
#LBL5 Автоматическое тестирование на тестовом наборе(может быть, я неправильно понял данный пункт)
#LBL6 Автоматическое сохранение и визуализация результатов тестирования(модель автоматически сохраняется)
#LBL7 Построение графиков, визуализирующих процесс обучения
#LBL8 Дополнительное улучшение(Сохранение модели с чекпоинта, на котором значение accuracy на валидации максимально)
#LBL9 Построение матрицы ошибок, оценивание чувствительности и специфичности модели
