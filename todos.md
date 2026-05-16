# Todos

## 1
Rate Limiting

Server still need to process request to check for rate limiting.  

The client request reaches server and then server checks for the rate limiting.  
My question is - any client can still bombard server with its requests, server will deny once rate limiting is reached but the point is request still reaches the server and server has to do work for the rate limit checks, this will keep the server busy all the time.  

## 2
DDoS Attack

