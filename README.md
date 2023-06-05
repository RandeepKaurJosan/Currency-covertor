# Currency-covertor
Here's a breakdown of the code:

Importing the required libraries:

tkinter is imported as tk for creating the graphical user interface.
tkinter.messagebox is imported for displaying error messages.
Creating the GUI:

The root window is created using tk.Tk().
The title of the window is set to "Currency converter: GeeksForGeeks".
A frame called Tops is created and placed at the top of the window for the heading.
The heading label is created and placed inside the Tops frame.
Two variables (variable1 and variable2) are created to store the selected currencies.
Default values for the variables are set as "currency".
Real-time currency conversion function:

The function RealTimeCurrencyConversion() is defined.
It uses the forex_python library to perform the currency conversion.
It retrieves the selected currencies and amount from the GUI elements.
If the amount is not entered or if the currencies are not selected, error messages are displayed.
Otherwise, it converts the amount from the source currency to the target currency and displays the result in the GUI.
Clearing the data:

The function clear_all() is defined to clear the entered data in the GUI fields.
It deletes the content of Amount1_field and Amount2_field.
Currency code list:

The list CurrenyCode_list contains the currency codes for various currencies.
Configuring the root window:

The background color and size of the window are set.
Creating and placing GUI elements:

Labels and Entry fields are created and placed in the grid layout using grid().
OptionMenus are created for selecting the currencies.
Convert and Clear All buttons are created with associated functions.
Empty labels are used for spacing.
Running the GUI:

The root.mainloop() method is called to start the GUI event loop.
