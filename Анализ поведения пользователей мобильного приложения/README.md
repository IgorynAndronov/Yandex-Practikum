**Тема проекта:** Анализ поведения пользователей мобильного приложения

**Исходные данные для анализа:** Записи в логе с действиями пользователя на сайте, указаны: название события, ID пользователя, время события и номер экспериментальной и контрольной группы.

**Задача:** Изучить воронку продаж, выяснить, на каком этапе "застревает" большая часть покупателей. Провести анализ результатов AB-теста по изменению шрифта во всем приложении, сделать вывод - как изменения в приложении влияют на продажи, стоит ли внедрять новый шрифт.  

**Этапы исследования:**
1. Открытие файла с данными и изучение общей информации, предообработка:

      - 1.1 Импорт библиотек, открытие и изучение файла
      - 1.2 Предобработка данных
      
2. Анализ данных;
3. Исследование воронки продаж:

      - 3.1 Распределение событий в логе
      - 3.2 Распределение пользователей по событиям в логе
      - 3.3 Распределение событий в логе по порядку
      - 3.4 Воронка событий в логе
      
4. Исследование результатов эксперимента:

      - 4.1 Проверка деления трафика
      - 4.2 Исследование результата в контрольных группах
      - 4.3 Исследование результата в тестовой группе


**Используемые библиотеки:**  pandas, numpy, matplotlib.pyplot, plotly, plotly.express, seaborn, scipy.stats, warnings
