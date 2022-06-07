Fork the repository privately (similar to https://gist.github.com/0xjac/85097472043b697ab57ba1b1c7530274) and set up these secrets in Settings -> Security -> Secrets:

(required) ShrimpyApiKey
-
(required) ShrimpyApiSecret
-
You can generate them in Shrimpy dashboard -> Settings -> Security & API -> API Keys

(required) NotificationEmail
-
E-mail address for notifications

(optional - required for adv. money management) state file name
-
tracker.state

(required) state file encryption key
-
256 bit encryption key in hex format

(optional) TargetBalance
-
default: 250.00

Target portfolio balance for all coins.

(optional) TakeprofitPercent
-
default: 7.00

Take profit level (in %).

(optional) RefillPercent
-
default: 7.00

Refill level (in %).

(optional) IgnoredSymbols
-
default: USDT,BTC

Ignores only BTC or only USDT single coin portfolios by default ("default" portfolios). 

(optional) IgnoredAccounts
-
default: none

format: comma separated list of ids

If you don't want to track certain portfolios you can provide the list of ids to disable them from notifications (the id is in the notification e-mail)



Adv. money management is done via github actions at the moment.

Full instructions to follow

