# Анализ результатов тестирования рекомендательной системы<a class="tocSkip">

**Цель исследования:**  
Проанализировать результаты проведенного А/В-тестирования изменений, связанных с внедрением улучшенной рекомендательной системы в интернет-магазине. Ожидаемый эффект: за 14 дней с момента регистрации в системе пользователи покажут улучшение каждой метрики не менее, чем на 10%:
- конверсии в просмотр карточек товаров — событие `product_page`;
- просмотры корзины — `product_cart`;
- покупки — `purchase`.  
  
Аудитория: 15% новых пользователей из региона EU.  
  
Ожидаемое количество участников теста: 6000.  
  
**Исходные данные:**  
Данные о пользователях, зарегистрировавшихся в интернет-магазине в период с 7 по 21 декабря 2020 года , события пользователей в период тестирования с 7 декабря 2020 по 4 января 2021 года и календарь маркетинговых событий на 2020 год. 
    
**Задачи исследования:**  

1. Изучение общей информации. Проведение предобработки данных:
    - проверить корректность названия столбцов и заменить (при необходимости);
    - преобразовать данные в нужные типы (при необходимости);
    - обработать пропуски (при наличии);
    - обработать дубликаты (при необходимости).    
    
   
2. Исследовательский анализ данных:  
   - выяснить присутствуют ли в выборках одни и те же пользователи;
   - выяснить есть ли в данных ещё какие-то особенности, которые нужно учесть, прежде чем приступать к A/B-тестированию;
   - изучить как число событий распределено по дням;
   - проверить обладают ли выборки одинаковыми распределениями количества событий на пользователя;
   - изучить конверсию в воронке на разных этапах.
   
   
3. Оценка результатов A/B-тестирования:
   - проверить статистическую разницу долей z-критерием;
   - оценить результаты A/B-тестирования. 
   
  
4. Выводы и рекомендации. 
