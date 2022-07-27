# ft_userdata
# ft_userdata
docker-compose run --rm freqtrade download-data --pairs BTC/USDT --exchange binance --days 36500 -t 15m --trading-mode futures       
docker-compose run --rm freqtrade backtesting --config user_data/config.json --strategy SampleStrategy --starting-balance 999999     
