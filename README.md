# MyCurrencyconverter
# DESCRIPTION
This is basic currency converter web page. Users can input an amount, select target currencies, and click the "Convert" button to see the converted amount. The conversion rates are defined in the JavaScript code, allowing for custom rates.
# KEY FEATURES
- HTML Structure:
  
The code starts with the usual HTML5 document structure, including the <!DOCTYPE html> declaration.
Inside the <head> section, there's a title for the web page, which is set to "Currency Converter."
- Page Title:
  
The page contains an h1 element with the title "Currency Converter," providing a clear heading for the converter.
Input Section:
There are three main input elements:
<input type="number" id="amount" placeholder="Enter amount">: This input field allows users to enter the amount they want to convert. It only accepts numeric values.
<select id="fromCurrency">: This dropdown menu lets users select the currency they want to convert from.
<select id="toCurrency">: Similar to the previous dropdown, this one allows users to choose the target currency for conversion.

- Conversion Button:
  
There is a <button> element with the text "Convert." When clicked, it triggers the convertCurrency() JavaScript function to perform the conversion.

- Result Display:
  
A p element with the id="result" is used to display the conversion result. The result will appear as a formatted string, showing the original amount, source currency, and converted amount with the target currency.

- JavaScript Logic:
  
The JavaScript code embedded in the <script> section handles the currency conversion.
It defines a JavaScript object called exchangeRates, which stores custom exchange rates relative to the Canadian Dollar (CAD). These rates are used for currency conversion.
The convertCurrency() function is called when the "Convert" button is clicked. It performs the following steps:
Retrieves the user-entered amount, source currency, and target currency from the input elements.
Checks if the amount entered is a valid number using isNaN(). If not, it displays an alert.
Verifies that the source and target currencies are different. If they are the same, it displays an alert.
Calculates the converted amount based on the exchange rates and updates the result display.

# VISUAL REPRESENTATION
<img width="1440" alt="Screenshot 2023-10-06 at 11 09 59 PM" src="https://github.com/SylvieNdifor/MyCurrencyconverter/assets/147012281/355ff3a0-2efe-4e8f-b111-6cc20982fbde">


# CONTRIBUTIONS
Thank you for considering contributing to MyPomodoro! All contributions from the community to help improve and enhance this project are welcomed. Whether you're fixing a bug, adding a feature, or improving documentation, your contributions are highly appreciated. For new features or enhancements. Please open an issue to discuss your ideas. If you encounter a bug, please open an issue to report it.
