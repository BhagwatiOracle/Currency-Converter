## 💱 Currency Converter using LangChain and OpenAI
This project is a simple yet intelligent Currency Converter built with LangChain and OpenAI's API. It utilizes tool-based function calling to fetch real-time conversion rates and compute currency values from one unit to another.


## 🛠️ Features
🌍 Converts between any two global currencies.



## 🔧 Uses two modular tools:

* get_conversion_factor – Fetches the current exchange rate between a base and target currency.

* convert – Computes the converted amount using the fetched exchange rate.

* 💡 Powered by OpenAI's function-calling capability through LangChain.

## 🧠 How It Works
1. User Input: The user specifies the base currency, target currency, and amount.

2. Function Call: LangChain routes the request through OpenAI, which uses the get_conversion_factor tool to get the live exchange rate.

3. Computation: The convert tool then calculates the amount in the target currency.

4. Response: The converted currency value is returned to the user in a friendly format.
