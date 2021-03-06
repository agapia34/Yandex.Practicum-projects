# Аналитика бизнес-показателей Яндекс.Афиши

**Цель исследования** – отказаться от невыгодных источников трафика и перераспределить бюджет отдела маркетинговой аналитики Яндекс.Афиши. Для этого были предоставлены следующие данные:
- лог сервера с данными о посещениях сайта Яндекс.Афиши (датафрейм `visits`);
- выгрузка всех заказов за этот период (датафрейм `orders`);
- статистика рекламных расходов (датафрейм `costs`).

**В рамках проекта было исследовано:**
- как клиенты пользуются сервисом;
- когда делают первые покупки на сайте;
- сколько денег приносит компании каждый клиент;
- когда расходы на привлечение клиента окупаются.

**Для этого были рассчитаны:**
- продуктовые метрики: DAU, WAU, MAU, среднее количество посещений пользователей за день, среднее количество времени, которое пользователи проводят на сайте, retention rate;
- метрики электронной коммерции: среднее количество времени с момента первого посещения сайта до совершения покупки, среднее количество покупок на одного покупателя за 6 месяцев, средний чек и LTV покупателя по когортам;
- маркетинговые метрики: общая сумма расходов на маркетинг по источникам, средний CAC на одного покупателя для всего проекта и для каждого источника трафика, ROMI по когортам в разрезе источников.

По итогу были представлены выводы по всем источникам трафика, информация о пользователях, выбраны лучшие и худшие источники трафика.

Для выполнения проекта были использованы библиотеки Pandas, Numpy, Matplotlib, Pylab.
