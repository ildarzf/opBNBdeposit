# opBNB Deposit

Для работы скрипта потребуется gETH или tBNB 
Используем два скрипта.

1.GETH-tBnb.py свапает через Zetachain % от остатка на счете gETH в tBNB (так как доходят не сразу сеть тестовая могут быть задержки до 10 минут). Загоняем пачку кошельков ждем поступления (10 минут хватит)

Проверить поступление можно тут https://testnet.bscscan.com/

2. tBNB-opBnb.py гонит через оф.мост ( https://opbnb-testnet-bridge.bnbchain.org/). Приходит минут за 5.
   
wallets.txt вводим приватники 1 приватник одна строчка.

В каждом файле можно менять

############################################  ИЗМЕНЯЕМЫЕ ПАРАМЕТРЫ  #######################################

TST_FROM = 8 # от в процентах от баланса

TST_TO = 16 # до в процентах


wal_sleep_min = 70    # минимальная задержка между кошелька

wal_sleep_max = 120    # максимальная задержка между кошелька

###########################################################################################################

DONATE на тесты скриптов (evm) : 0xe7b5cb9f137C663D07EF2539678392650c8e3645

Telegram channel https://t.me/ildar_scripts

Telegram https://t.me/ildarzf

Telegram chat https://t.me/ildarscriptschat
