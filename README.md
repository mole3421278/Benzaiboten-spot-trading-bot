# Benzaiboten-spot-trading-bot
A trading bot easy to use to be linked to your favorite exchange to automatize the trading on cryptocurrencies

# <p align="center">BENZAIBOTEN<br>(a crypto trading optimizer bot)</p>
A bot to automatize the crypto trading on Binance (twin of [Daibotuten](https://github.com/mole3421278/Daibotuten-futures-trading-optimizer-bot))
# Warning: Do your own research to decide on which cryptocurrencies the bot should do trading (blacklist the other cryptocurrencies)
# DO NOT USE during Black Swan events...
The bot finds the best cryptocurrencies to buy at each moment to resell them later. 

It uses an algorithm powered by AI to buy where an human would buy and at the same time trying to not stay with too much opened positions, so with it you don't have to worry about buying during the best moments.

It also shows to the user three indicators: 
- The fear and greed index of the current and previous day (lower values stand for fear and higher values stand for greed)
- The whale movements on chain
- The whale liquidations on the major exchanges (so to not be confused it with your own liquidations)

Use them to maximize the profit stopping and resuming the bot in the right times, following your own strategy.

There is also a display of the usdt balance, with a percentage about the daily profit (each day the percentage is reset), and you can click on the open positions you have to be redirected to the webpage of the chart.

Finally, the bot will notice you if a new version is available for the download.

# Settings
The bot leaves a high margin of customization to the user, to fit different strategies: you can change the settings whenever you think the market has changed, so do your own research to maximize the returns from it.

You can also leave the bot with its own standard settings if you are a newbie.


| Command  | Description | Possible Values |
| ------------- | ------------- | ------------- |
| **AMOUNT PER POSITION** | To choose how much to put at maximum in each position: in order to let the bot work well it is RECOMMENDED to have at LEAST 30 times the value you put here, so, if you choose 20 usdt it is RECOMMENDED that you have at least 600 usdt in the futures funds. However, it isn't a strict rule and so you can run the bot even with only 50 usdt. | The minimum value is 15 usdt and the maximum value is 50 usdt. |
| **PROFIT TO LEAVE** | To decide what percentage of the profit made with a cryptocurrency to leave in that cryptocurrency instead of converting everything back to usdt (if the profit is too low, everything is converted back to usdt in any case). | The minimum value is 0%, to sell all the quantity previously bought regardless of the profit done, and the maximum value is 100%, to sell only the quantity to cover the cost incurred when bought and to retain all the profit done in the cryptocurrency bought). |
| **STOP LOSS** | To decide when to close a position in case of loss. The bot has its own mechanism to take care of the potential loss, but you can overwrite it with this command. | The minimum value is 0% and it stands for "don't use stop loss" and the maximum value is 40%. |
| **TAKE PROFIT** | To decide when to close a position in case of profit. The bot has its own mechanism to take care of the potential profit, but you can overwrite it with this command. | The minimum value is 0% and it stands for "don't use take profit" and the maximum value is 30%. |
| **DON'T BUY IF BTC IS** | To force the bot to NOT buy ANYTHING if the price of BTC is over a certain threshold starting from the time in which it is set. | The minimum value is -10% and the maximum value is 10%. Put it to 0.0% to disable this behaviour. |
| **DON'T BUY IF ALT IS** | To force the bot to NOT buy the cryptocurrency if its price is over a certain threshold starting from the time in which it is set. | The minimum value is -30% and the maximum value is 30%. Put it to 0.0% to disable this behaviour. |
| **DON'T BUY FOR** | To force the bot to NOT buy the cryptocurrency for a certain interval of time | The minimum value is 0 hours and the maximum value is 12 hours. Put it to 0.0 hours to disable this behaviour. |
| **BUY IF CRASH OF** | To force the bot to buy ONLY IF in the last hour the price crashed from the maximum value to the current one of at least the percentage chosen | The minimum value is 0.0% hours and the maximum value is (-)15%. Put it to 0.0 to disable this behaviour. |
| **STOP AT NEXT WHALE LONG LIQUIDATION** | To stop the bot when there is a new whale long liquidation. The whale long liquidations can be seen in the bottom part of the bot, together with the whale short liquidations. | |
| **CLOSE** | To sell a cryptocurrency previously bought by the bot just by clicking a button: the bot is set to close them in the moment that it is the best for it, but if you want to close them before that moment, you can do it. | |
| **BLACKLIST** | To exclude certain cryptocurrencies to be bought by the bot depending on your own research just by typing their ticker symbol (so BTC for bitcoin) and then pressing ENTER. | All the tickers allowable to be traded that you haven't yet blacklisted (for example: ETH, BTC...). You can type ALL to blacklist every crypto, to whitelist only the ones that you want. Don't type other things here. |
| **WHITELIST** | To add again to the list of the bot a cryptocurrency that you excluded before just by typing its ticker symbol and then pressing ENTER. | All the tickers that you have previously blacklisted. You can type ALL to whitelist every crypto. Don't type other things here. |
| **STOP/RESUME** | To stop the bot with this button if you believe the market is entering in a bubble or in a big market crash, so you don't want to buy anything in that period. Clicking it again the bot will start to buy again. | |

Some parameters are settable even from the file settings_bot_spot.txt (expert mode, refer to this release: https://github.com/mole3421278/Benzaiboten-spot-trading-bot/releases/tag/v1.4.0)

# Activation
The bot can't be used from not authorized users.

**DON'T DELETE OR MOVE THE FILE settings_bot.txt otherwise you will have to activate the bot again**


# Requirements

The bot runs entirely in local, so it is important that the device where you install it has a good internet connection, otherwise you can incur in misbehaviour.

<p align="center"><img src="https://user-images.githubusercontent.com/91144525/140513103-88c402c6-772a-42f0-b4de-e88afe8469bc.png" width="720"></p>
<p align="center"><img src="https://user-images.githubusercontent.com/91144525/140513132-24b7c7c4-e017-49be-b400-f8440f70382e.png" width="720"></p>




# Notes

It can be that there are some minor bugs here and there. Please, do report them if you find them to improve the project.

If you have proposals to improve the project don't hesitate to post them.

For the moment it is in development a version for Windows.

In the future it will be expanded:
- to other exchanges;
- to other OS (first of all Android).

Please, use this repository to check for the updates.

If you intend to use also [Daibotuten](https://github.com/mole3421278/Daibotuten-futures-trading-optimizer-bot) you don't have to pay for it separately: the dev fee to pay is the same, so for 10 usdt per month you can use both of them.

# Latest release

https://github.com/mole3421278/Benzaiboten-spot-trading-bot/releases/latest

