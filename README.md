Сделать аналог интернет магазина. 

Реализовать возможность заказа продукта в магазине. Название товара и его стоимость генерируются рандомно (расходы продавцов за каждый заказ составляют 20). 

Реализовать возможности отправки товара для производства на ферму (цена фермерских расходов 100),а после - отправки клиенту (стоимость услуги 20).

Производить расчет полученных денег, всех расходов и прибыли.

Интерфейс представляет собой 3 блока:

1. Новые заказы (содержит 2 кнопки, одна создает заказ, вторая отправляет его на ферму. Сгенерированные товары храняться в блоке в виде списка. Элемент списка содержит название продукта, его цену, время заказа). После отправки товара на ферму товар из 1 блока перемещается во второй в порядке очереди.

2. Производство на ферме (содержит кнопку отправки заказа клиенту, после нажатия на которую первый товар, попавший в список из него изымается)

3. Бюджет. В этом блоке проводяться расчеты итоговой стоимости, суммарных расходов (которые обновляються после нажатий на кнопки из первых двух блоков) и прибыли.