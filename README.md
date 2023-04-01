# E-commerce project:
Стэк: Python (pandas, seaborn, matplotlib)

Цель:
-  Проведение разведывательного анализа данных;
-  Работа с метриками (расчет Retention на основе когортного анализа, построение RFM сегментации пользователей); 

Результат:
1. Выяснил сколько пользователей покупали товар только 1 раз.
2. Вывел статистику причин недоставки товара конечному потребителю.
3. Выявил самый покупаемый товар по дням недели. 
4. Построил когортный анализ пользователей и рассчитал когорту с самым высоким Retention на 3-й день.
5. Построил RFM-сегментацию пользователей для понимания, какие пользователи у нас самые активные.


Описание данных: 

- olist_customers_datase.csv — таблица с уникальными идентификаторами пользователей

customer_id — позаказный идентификатор пользователя

customer_unique_id —  уникальный идентификатор пользователя  (аналог номера паспорта)

customer_zip_code_prefix —  почтовый индекс пользователя

customer_city —  город доставки пользователя

customer_state —  штат доставки пользователя



- olist_orders_dataset.csv —  таблица заказов

order_id —  уникальный идентификатор заказа (номер чека)

customer_id —  позаказный идентификатор пользователя

order_status —  статус заказа

order_purchase_timestamp —  время создания заказа

order_approved_at —  время подтверждения оплаты заказа

order_delivered_carrier_date —  время передачи заказа в логистическую службу

order_delivered_customer_date —  время доставки заказа

order_estimated_delivery_date —  обещанная дата доставки



- olist_order_items_dataset.csv —  товарные позиции, входящие в заказы

order_id —  уникальный идентификатор заказа (номер чека)

order_item_id —  идентификатор товара внутри одного заказа

product_id —  ид товара (аналог штрихкода)

seller_id — ид производителя товара

shipping_limit_date —  максимальная дата доставки продавцом для передачи заказа партнеру по логистике

price —  цена за единицу товара

freight_value —  вес товара
