# Stock-Price-Alerter
The following project is aimed to notify you through whatsapp when the price of a selected stock goes down by a certain value. (An alternative for stop-loss)

The module takes in the minimum price you accept the stock to go to. It then keeps track of the current price from moneycontrol. If it sees that the price has dipped below the price, it will send out an alert through whatsapp to the aforementioned number using pywhatkit.
