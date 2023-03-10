# **Сборный проект: "Изучение причин убытков компании"**

## **Данные**
Данные о посещениях пользователей:  
- User Id - уникальный идентификатор пользователя	 
- Region - страна  
- Device - устройство входа  
- Channel - канал привлечения пользователя  
- Session Start	- начало сессии  
- Session End - конец сессии

Данные о покупках:  
- User Id - уникальный идентификатор пользователя
- Event Dt - дата покупки 
- Revenue - стоимость покупки

Рекламные расходы:  
- dt - дата расходов
- Channel - канал привлечения пользователя
- costs - стоимость рекламы

## **Задача**

Разобраться в причинах убытков и помочь компании выйти в плюс. Расчет и визуализация LTV, CAC, ROI.

## **Итоговые выводы**
Причины неэффективности привлечения пользователей

    Нерациональное распределение затрат на рекламу. Максимальные затраты приходятся на США - каналы TipTop и FaceBoom, при этом выручка с них минимальна, они стабильно не окупаются, как и канал AdNonSense
    Снижены затраты на каналы RocketSuperAds, YRabbit, MediaTornado - хотя они достаточно ликвидны
    Плохое удержание пользователей из США, которые составляют основную часть аудитории.
    Не была вовремя учтена сезонность кампании - окупаемость начала падать с конца июня - вероятно, тогда же вышел продукт конкурентов, пользующийся бОльшим спросом
    Падение удержания пользователей устройств Apple - нужно исследовать отдельно, возможно, есть ряд технических проблем в работе приложения на данных осях

Рекомендации для отдела маркетинга для повышения эффективности

    Переформатировать затраты на рекламу по странам: сфокусироваться вместо аудитории США на аудиторию из Великобритании и Германии - там хорошая окупаемость
    Пересмотреть работу с аудиторией Германии - там хорошая окупаемость, но нестабильное удержание летом
    Пересмотреть работу с аудиторией из Великобритании - там присутствует сезонность, можно взять под конец лета - начало осени траффик у AdNonSense, например
    Пересмотреть политику удержания во Франции
    Расширить географию продукта
    Перераспределить затраты на рекламу по каналам: уменьшить бюджет на TipTop и уменьшить бюджет\отказаться от канала FaceBoom и перенаправить его на более эффективный канал, например, YRabbit, при минимальных затратах он дает хороший показатель выручки. 
    Также перспективными выглядят каналы RocketSuperAds, MediaTornado
    Канал AdNonSense использовать только на сезонное привлечение (конец лета - осень)
    Попробовать использовать новые рекламные каналы
    Обратить внимание на пользователей Mac и iPhone: стоимость их привлечения высока, а окупаемоcть страдает - отдельно проработать вопрос привлечения этой категории пользователей


## **Используемые библиотеки**

pandas, numpy, matplotlib, datetime
