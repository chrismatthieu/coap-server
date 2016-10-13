# CoAP Server
Quick CoAP server demo

## Getting Started
> npm install

> npm start

## Testing

> npm install coap-cli -g

> coap get coap://localhost/chris

## Deploy to Tessel

> t2 wifi -n network -p password

> t2 run index.js -OR- t2 push index.js

> coap get coap://192.168.100.93/chris

(2.05)	Hello chris
