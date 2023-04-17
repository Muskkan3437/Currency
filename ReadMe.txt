The currency exchange rates are obtained from the "https://api.exchangerate-api.com/v4/latest/USD" API using a GET request. The exchange rates are stored in a dictionary called Price.

A list of available currencies is created by getting the keys of the Price dictionary.

The script creates input widgets to allow the user to enter the amount of money to convert, select the currency to convert from, and select the currency to convert to.

A conversion function is created that converts the input amount from the currency selected in the "From" dropdown menu to the currency selected in the "To" dropdown menu using the exchange rates obtained from the Price dictionary. The result is displayed in a label on the screen.

A "Convert" button is created that calls the conversion function when clicked.

A "Reset" button is created that clears the input widgets and result label when clicked.

Finally, the Tkinter event loop is started using the mainloop() method, which keeps the GUI running and waiting for user input until the user closes the window.