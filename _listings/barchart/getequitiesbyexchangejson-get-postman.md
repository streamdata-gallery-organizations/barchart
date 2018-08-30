{
  "info": {
    "name": "Barchart API Get Equities by Exchange",
    "_postman_id": "4b2d7f5d-0a56-4242-9c11-a655b0a2be5f",
    "description": "Receive all real-time or delayed stock and/or index price data by exchange through a single onDemand query.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Quotes",
      "item": [
        {
          "id": "54108991-e761-49be-9789-1e574e197aec",
          "name": "getQuote",
          "request": {
            "url": "http://marketdata.websol.barchart.com/getQuote.json?symbols=symbols",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "The getQuote API is used to request price data, either real-time, delayed or end-of-day, by symbol. In addition to Last Price or Settlement, other fields such as Open, High, Low, Close, Bid, Ask, 52-week high and low, and more are available."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7cdd4d3a-035b-45ed-bda8-757bf5d46212"
            }
          ]
        }
      ]
    },
    {
      "name": "Equities",
      "item": [
        {
          "id": "4acc408d-4e14-4635-ade7-46a635261837",
          "name": "getEquitiesByExchange",
          "request": {
            "url": "http://marketdata.websol.barchart.com/getEquitiesByExchange.json?symbols=symbols",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Receive all real-time or delayed stock and/or index price data by exchange through a single onDemand query."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "81146281-1e49-4c4f-9863-c4bee6ba03d8"
            }
          ]
        }
      ]
    }
  ]
}