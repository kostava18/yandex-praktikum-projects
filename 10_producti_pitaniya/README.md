# Проект Анализ пользовательского поведения в мобильном приложении

*Статус: завершен*

## Цель проекта

На основе данных использования мобильного приложения для продажи продуктов питания проанализировать воронку продаж, а также оценить результаты A/A/B-тестирования. 

## Вывод

На основании результатов A/A/B-теста мы считаем, что изменение шрифтов не приведет к изменению поведения пользователей. Можно изменить шрифты, если это не стоит компании существенных ресурсов или даст иные бенефиты, кроме изменения конверсии. В ином случае изменени шрифтов не приведет ни к чему, кроме траты ресурсов.

## Данные

logs_exp:  
`DeviceIDHash` - идентификтор пользователя  
`EventTimestamp` - время события  
`EventName` - название события  
`ExpId` - номер эксперимента, где 246 и 247 - контрольные группы, а 248 - экспериментальная  

## Библиотеки

- Pandas
- Datetime
- Numpy
- Math
- Scipy
- Matplotlib
- Seaborn
- Plotly
