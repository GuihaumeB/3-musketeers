# cash
Display the conversion of an amount of cash through a currency exchange rate API/

The command line accepts the following arguments:

    - amount
    - currency (EUR, USD, GBP, JPY...)
    - currency to convert to

The default output is:

    Conversion of 1 USD
    to EUR, GBP and JPY
    

#Installation
    - Run "npm install i" in this folder
    
#Examples
    - node index.js
    - node index.js 10 EUR
    - node index.js 10 EUR JPY
    - node index.js --set JPY SEK