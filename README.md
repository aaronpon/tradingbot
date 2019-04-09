# tradingbot
Binance Trading


Install java and maven, and run:


git clone git@github.com:binance-exchange/binance-java-api.git
cd binance-java-api
mvn clean install
cd ..
git clone git@github.com:huntingthecoins/binance-trader.git
cd binance-trader
mvn spring-boot:run -DAPI_KEY=$YOUR_API_KEY -DAPI_SECRET=$YOUR_API_SECRET


