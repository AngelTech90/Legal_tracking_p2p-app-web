
App need to make easier keep a legal tracking of every single one of our clients in p2p market.

## Core features:
**Non-verfied advertiser and verified advertiser switch**
**Capital input with popup**
**Inherit commission in your capital changing of 0.20% to **
**Calcular tasa button with popup that set "precio de entrada (red)" and "precio de salida(green)"**
**Automatic amount in VES data visualization when "tasa" is setted**
**Set daily cicles popup**
**Set your p2p profile section with a popup with a form**
**Data visualization of how many days you will take to be verified, get enough 1-btc 30-days volume and total 2-btc volume and total compound days**
**Data visualization of your monthly earnings**
**Data visualization of you you earnings per cycle**

## Funcionalities:
Got inherit calculation to commisions relative to the total capital

Got earnings in a percentage, this percentage will be calculated multiplying (capital-commision) with Selling price (precio de salida) and then dividing it with buying price (precio de salida) ((capital-comiission)*sellingprice)/buyingprice) this is our USD earnings per cycle, and for calculate earnings in percentage we got (((earningpercycle.100)/capital)-100)/100

Got earnings in USD per cycle (capital-(((capital-comssion)*sellingprice)/buyingprice))

Got total earnings per day in USD (earningspercycle*totaldayscycle)

Got using a public and free API for got BTC/USD price, then we'll calculate our trading volume relative to reach equivalent to 2 btc, our volume will be calculted using our daily cicles taking in count our earnings per cycle too, and using this values as equivalent to 1 day data and calculating the days that we'll take to got 2-btc, you just get 1-btc value in USD, you multiply it per 2, then you rest it with current user BTC volume (that i default it it's 0), you divide that with his capital and then with his daily cycles.

Got with the 1 btc value in USD you just need too get 1-btc value in usd, you multiply it per 1, then you rest it with current 30 days btc volume of user (that by default it's 0), you dive that with his capital and then his daily cycles
 
